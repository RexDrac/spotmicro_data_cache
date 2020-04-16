render-eval: False
critic-weight-decay: 1e-06
max-test-time: 10
test-num: 4
batch-size: 128
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
action-dim: 12
joint-interpolation: True
max-train-time: 10
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
categorical-distribution: {'n_atoms': 51, 'v_min': -10, 'v_max': 250}
max-episode-num: 5000000
tau: 0.001
actor-layer-size: [256, 256]
rollout-step-num: 1
dsr-gait-period: 0.6
squash-action: True
actor-lr: 0.0003
Physics-frequency: 1000
state-dim: 20
epoch-num: 500
task-weight: 0.5
critic-lr: 0.0003
replay-buffer-size: 1000000
actor-weight-decay: 1e-06
actor-activation-fn: ['relu', 'relu', 'None']
critic-activation-fn: ['relu', 'relu', 'None']
reward-scale: 0.1
imitation-weight: 0.5
critic-layer-size: [256, 256]
interpolation: False
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
expert-num: 4
total-step-num: 2500000000
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
prioritized-exp-replay: True
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
filter-torque: False
replay-ratio: 1
env-id: HumanoidBalanceFilter-v0
replay-start-size: 10000
gating-activation-fn: ['relu', 'relu', 'None']
loss-output-bound-coeff: 0.0
LLC-frequency: 500
train-step-num: 1
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
record-start-size: 10000.0
epoch-step-num: 5000000
filter-action: True
gating-index: None
max-step-num: 2500000000
gamma: 0.955
expert-index: None
actor-l2-reg: 0.0003
gating-layer-size: [32, 32]
max-path-num: 20
loss-output-diff-coeff: 0
n-step: 1
action-bounds: [[-0.5236 -2.666  -0.1    -0.5236 -2.666  -0.1    -0.5236 -2.666  -0.1
  -0.5236 -2.666  -0.1   ]
 [ 0.5236  1.548   2.09    0.5236  1.548   2.09    0.5236  1.548   2.09
   0.5236  1.548   2.09  ]]
dsr-gait-freq: 1.667
critic-l2-reg: 0.0003
bullet-default-PD: False
loss-output-smooth-coeff: 1.0
loss-entropy-coeff: 0.0
HLC-frequency: 25
max-path-step: 5000
