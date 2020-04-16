actor-l2-reg: 0.0003
loss-output-bound-coeff: 0.0
tau: 0.001
expert-num: 4
train-step-num: 1
HLC-frequency: 25
batch-size: 128
gating-index: None
max-test-time: 10
action-bounds: [[-0.5236 -2.666  -0.1    -0.5236 -2.666  -0.1    -0.5236 -2.666  -0.1
  -0.5236 -2.666  -0.1   ]
 [ 0.5236  1.548   2.09    0.5236  1.548   2.09    0.5236  1.548   2.09
   0.5236  1.548   2.7925]]
task-weight: 0.0
loss-entropy-coeff: 0.0
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
epoch-step-num: 5000000
reward-scale: 0.1
gating-activation-fn: ['relu', 'relu', 'None']
Physics-frequency: 1000
imitation-weight: 1.0
prioritized-exp-replay: True
n-step: 1
joint-interpolation: True
interpolation: False
actor-layer-size: [256, 256]
env-id: HumanoidBalanceFilter-v0
filter-action: True
max-train-time: 10
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
max-episode-num: 5000000
actor-lr: 0.0003
gamma: 0.995
max-step-num: 2500000000
critic-weight-decay: 1e-06
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
LLC-frequency: 500
epoch-num: 500
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
categorical-distribution: {'n_atoms': 51, 'v_min': -10, 'v_max': 250}
replay-start-size: 10000
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
total-step-num: 2500000000
loss-output-smooth-coeff: 1.0
max-path-num: 20
critic-layer-size: [256, 256]
critic-lr: 0.0003
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
max-path-step: 5000
action-dim: 12
replay-ratio: 1
critic-activation-fn: ['relu', 'relu', 'None']
test-num: 4
rollout-step-num: 1
filter-torque: False
actor-activation-fn: ['relu', 'relu', 'None']
expert-index: None
critic-l2-reg: 0.0003
squash-action: True
state-dim: 18
bullet-default-PD: False
loss-output-diff-coeff: 0
replay-buffer-size: 1000000
record-start-size: 10000.0
actor-weight-decay: 1e-06
gating-layer-size: [32, 32]
render-eval: False
