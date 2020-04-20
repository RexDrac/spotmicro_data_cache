actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
bullet-default-PD: False
train-step-num: 1
expert-num: 4
state-dim: 20
Physics-frequency: 1000
joint-interpolation: True
epoch-num: 500
critic-l2-reg: 0.0003
actor-activation-fn: ['relu', 'relu', 'None']
gating-layer-size: [32, 32]
loss-output-diff-coeff: 0
max-path-step: 5000
action-bounds: [[-0.5236 -2.666  -0.1    -0.5236 -2.666  -0.1    -0.5236 -2.666  -0.1
  -0.5236 -2.666  -0.1   ]
 [ 0.5236  1.548   2.09    0.5236  1.548   2.09    0.5236  1.548   2.09
   0.5236  1.548   2.09  ]]
interpolation: False
tau: 0.001
total-step-num: 2500000000
HLC-frequency: 25
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
n-step: 1
critic-activation-fn: ['relu', 'relu', 'None']
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
test-num: 4
filter-torque: False
reward-scale: 0.1
batch-size: 128
expert-index: None
replay-buffer-size: 1000000
rollout-step-num: 1
actor-layer-size: [256, 256]
epoch-step-num: 5000000
actor-weight-decay: 1e-06
max-path-num: 20
max-step-num: 2500000000
critic-layer-size: [256, 256]
max-train-time: 10
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
max-episode-num: 5000000
replay-ratio: 1
record-start-size: 10000.0
task-weight: 0.5
filter-action: True
action-dim: 12
dsr-gait-freq: 1.667
max-test-time: 10
render-eval: False
actor-lr: 0.0003
loss-output-smooth-coeff: 1.0
critic-weight-decay: 1e-06
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
categorical-distribution: {'n_atoms': 51, 'v_min': -10, 'v_max': 250}
LLC-frequency: 500
actor-l2-reg: 0.0003
loss-output-bound-coeff: 0.0
prioritized-exp-replay: True
imitation-weight: 0.5
env-id: HumanoidBalanceFilter-v0
gating-index: None
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
replay-start-size: 10000
gamma: 0.955
dsr-gait-period: 0.6
critic-lr: 0.0003
loss-entropy-coeff: 0.0
gating-activation-fn: ['relu', 'relu', 'None']
squash-action: True
