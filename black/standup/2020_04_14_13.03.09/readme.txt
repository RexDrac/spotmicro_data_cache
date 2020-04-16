loss-output-smooth-coeff: 1.0
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
env-id: HumanoidBalanceFilter-v0
max-test-time: 10
tau: 0.001
action-bounds: [[-0.5236 -2.666  -0.1    -0.5236 -2.666  -0.1    -0.5236 -2.666  -0.1
  -0.5236 -2.666  -0.1   ]
 [ 0.5236  1.548   2.09    0.5236  1.548   2.09    0.5236  1.548   2.09
   0.5236  1.548   2.09  ]]
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
max-step-num: 2500000000
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-l2-reg: 0.0003
n-step: 1
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
actor-weight-decay: 1e-06
categorical-distribution: {'n_atoms': 51, 'v_min': -10, 'v_max': 250}
epoch-step-num: 5000000
LLC-frequency: 500
critic-l2-reg: 0.0003
total-step-num: 2500000000
loss-output-diff-coeff: 0
epoch-num: 500
actor-lr: 0.0003
replay-ratio: 1
loss-entropy-coeff: 0.0
actor-activation-fn: ['relu', 'relu', 'None']
joint-interpolation: True
test-num: 4
filter-torque: False
Physics-frequency: 1000
critic-lr: 0.0003
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
expert-num: 4
render-eval: False
loss-output-bound-coeff: 0.0
train-step-num: 1
max-path-step: 5000
HLC-frequency: 25
interpolation: False
actor-layer-size: [256, 256]
record-start-size: 10000.0
gating-layer-size: [32, 32]
filter-action: True
max-path-num: 20
replay-start-size: 10000
prioritized-exp-replay: True
critic-layer-size: [256, 256]
max-episode-num: 5000000
expert-index: None
imitation-weight: 1.0
task-weight: 0.0
gating-activation-fn: ['relu', 'relu', 'None']
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
replay-buffer-size: 1000000
max-train-time: 10
critic-weight-decay: 1e-06
rollout-step-num: 1
bullet-default-PD: False
state-dim: 18
critic-activation-fn: ['relu', 'relu', 'None']
reward-scale: 0.1
batch-size: 128
action-dim: 12
squash-action: True
gamma: 0.995
gating-index: None
