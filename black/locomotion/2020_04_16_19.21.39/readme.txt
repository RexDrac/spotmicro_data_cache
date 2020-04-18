loss-output-smooth-coeff: 0.5
tau: 0.001
action-bounds: [[-0.5236 -2.666  -0.1    -0.5236 -2.666  -0.1    -0.5236 -2.666  -0.1
  -0.5236 -2.666  -0.1   ]
 [ 0.5236  1.548   2.09    0.5236  1.548   2.09    0.5236  1.548   2.09
   0.5236  1.548   2.09  ]]
expert-num: 4
train-step-num: 1
render-eval: False
reward-scale: 0.1
replay-buffer-size: 1000000
gamma: 0.955
actor-weight-decay: 1e-06
interpolation: False
replay-start-size: 10000
imitation-weight: 0.5
critic-activation-fn: ['relu', 'relu', 'None']
prioritized-exp-replay: True
rollout-step-num: 1
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
epoch-num: 500
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
max-test-time: 10
critic-weight-decay: 1e-06
dsr-gait-freq: 1.667
categorical-distribution: {'n_atoms': 51, 'v_min': -10, 'v_max': 250}
state-dim: 20
max-path-step: 5000
max-path-num: 20
actor-layer-size: [256, 256]
max-episode-num: 5000000
epoch-step-num: 5000000
critic-lr: 0.0003
max-step-num: 2500000000
gating-activation-fn: ['relu', 'relu', 'None']
batch-size: 128
test-num: 4
dsr-gait-period: 0.6
expert-index: None
critic-layer-size: [256, 256]
max-train-time: 10
loss-output-diff-coeff: 0
actor-l2-reg: 0.0003
action-dim: 12
Physics-frequency: 1000
filter-torque: False
bullet-default-PD: False
squash-action: True
gating-index: None
total-step-num: 2500000000
gating-layer-size: [32, 32]
replay-ratio: 1
filter-action: True
LLC-frequency: 500
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
joint-interpolation: True
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
env-id: HumanoidBalanceFilter-v0
loss-entropy-coeff: 0.0
critic-l2-reg: 0.0003
n-step: 1
actor-activation-fn: ['relu', 'relu', 'None']
loss-output-bound-coeff: 0.0
actor-lr: 0.0003
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
task-weight: 0.5
HLC-frequency: 25
record-start-size: 10000.0
