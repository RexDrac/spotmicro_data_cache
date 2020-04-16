LLC-frequency: 500
replay-buffer-size: 1000000
render-eval: False
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
action-dim: 12
gating-index: None
joint-interpolation: True
max-episode-num: 5000000
squash-action: True
categorical-distribution: {'n_atoms': 51, 'v_max': 250, 'v_min': -10}
test-num: 4
interpolation: False
prioritized-exp-replay: True
n-step: 1
loss-output-bound-coeff: 0.0
rollout-step-num: 1
max-test-time: 10
critic-l2-reg: 0.0003
gamma: 0.995
critic-lr: 0.0003
loss-entropy-coeff: 0.0
train-step-num: 1
filter-action: True
total-step-num: 2500000000
max-path-num: 20
actor-activation-fn: ['relu', 'relu', 'None']
bullet-default-PD: False
critic-activation-fn: ['relu', 'relu', 'None']
replay-start-size: 10000
actor-weight-decay: 1e-06
batch-size: 128
max-train-time: 10
epoch-num: 500
state-dim: 18
tau: 0.001
loss-output-diff-coeff: 0
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-l2-reg: 0.0003
Physics-frequency: 1000
max-path-step: 5000
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
expert-num: 4
imitation-weight: 1.0
HLC-frequency: 25
epoch-step-num: 5000000
record-start-size: 10000.0
expert-index: None
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
critic-layer-size: [256, 256]
max-step-num: 2500000000
task-weight: 0.0
critic-weight-decay: 1e-06
replay-ratio: 1
filter-torque: False
action-bounds: [[-0.5236 -2.666  -0.1    -0.5236 -2.666  -0.1    -0.5236 -2.666  -0.1
  -0.5236 -2.666  -0.1   ]
 [ 0.5236  1.548   2.09    0.5236  1.548   2.09    0.5236  1.548   2.09
   0.5236  1.548   2.7925]]
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
env-id: HumanoidBalanceFilter-v0
gating-layer-size: [32, 32]
actor-lr: 0.0003
loss-output-smooth-coeff: 1.0
gating-activation-fn: ['relu', 'relu', 'None']
actor-layer-size: [256, 256]
reward-scale: 0.1
