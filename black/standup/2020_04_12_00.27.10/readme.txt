gating-index: None
record-start-size: 10000.0
prioritized-exp-replay: True
expert-index: None
filter-action: True
total-step-num: 2500000000
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
interpolation: False
rollout-step-num: 1
env-id: HumanoidBalanceFilter-v0
loss-entropy-coeff: 0.0
critic-weight-decay: 1e-06
gating-activation-fn: ['relu', 'relu', 'None']
actor-activation-fn: ['relu', 'relu', 'None']
filter-torque: False
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
epoch-step-num: 5000000
reward-scale: 0.1
tau: 0.001
task-weight: 0.0
max-episode-num: 5000000
gamma: 0.995
gating-layer-size: [32, 32]
bullet-default-PD: False
joint-interpolation: True
actor-weight-decay: 1e-06
max-train-time: 10
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
critic-lr: 0.0003
max-test-time: 10
max-path-step: 5000
actor-l2-reg: 0.0003
max-step-num: 2500000000
critic-l2-reg: 0.0003
replay-buffer-size: 1000000
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
expert-num: 4
batch-size: 128
action-dim: 12
test-num: 4
critic-activation-fn: ['relu', 'relu', 'None']
squash-action: True
loss-output-diff-coeff: 0
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
actor-lr: 0.0003
train-step-num: 1
state-dim: 18
epoch-num: 500
replay-start-size: 10000
categorical-distribution: {'n_atoms': 51, 'v_min': -10, 'v_max': 250}
LLC-frequency: 500
loss-output-smooth-coeff: 1.0
n-step: 1
loss-output-bound-coeff: 0.0
imitation-weight: 1.0
critic-layer-size: [256, 256]
action-bounds: [[-0.5236 -2.666  -0.1    -0.5236 -2.666  -0.1    -0.5236 -2.666  -0.1
  -0.5236 -2.666  -0.1   ]
 [ 0.5236  1.548   2.09    0.5236  1.548   2.09    0.5236  1.548   2.09
   0.5236  1.548   2.7925]]
render-eval: False
actor-layer-size: [256, 256]
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
Physics-frequency: 1000
max-path-num: 20
HLC-frequency: 25
replay-ratio: 1
