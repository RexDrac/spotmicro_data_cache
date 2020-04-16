bullet-default-PD: False
n-step: 1
action-bounds: [[-0.5236 -2.666  -0.1    -0.5236 -2.666  -0.1    -0.5236 -2.666  -0.1
  -0.5236 -2.666  -0.1   ]
 [ 0.5236  1.548   2.09    0.5236  1.548   2.09    0.5236  1.548   2.09
   0.5236  1.548   2.7925]]
gamma: 0.995
filter-torque: False
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-lr: 0.0003
actor-layer-size: [256, 256]
expert-num: 4
record-start-size: 10000.0
tau: 0.001
expert-index: None
Physics-frequency: 1000
gating-activation-fn: ['relu', 'relu', 'None']
loss-output-smooth-coeff: 1.0
max-test-time: 10
max-path-step: 5000
actor-activation-fn: ['relu', 'relu', 'None']
critic-lr: 0.0003
state-dim: 18
reward-scale: 0.1
task-weight: 0.0
loss-entropy-coeff: 0.0
rollout-step-num: 1
replay-buffer-size: 1000000
critic-layer-size: [256, 256]
critic-weight-decay: 1e-06
epoch-step-num: 5000000
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
critic-activation-fn: ['relu', 'relu', 'None']
interpolation: False
gating-index: None
gating-layer-size: [32, 32]
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
prioritized-exp-replay: True
render-eval: False
HLC-frequency: 25
total-step-num: 2500000000
critic-l2-reg: 0.0003
batch-size: 128
epoch-num: 500
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
action-dim: 12
loss-output-bound-coeff: 0.0
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
imitation-weight: 1.0
actor-l2-reg: 0.0003
joint-interpolation: True
max-train-time: 10
test-num: 4
replay-start-size: 10000
max-path-num: 20
loss-output-diff-coeff: 0
actor-weight-decay: 1e-06
max-step-num: 2500000000
max-episode-num: 5000000
replay-ratio: 1
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
squash-action: True
LLC-frequency: 500
env-id: HumanoidBalanceFilter-v0
train-step-num: 1
categorical-distribution: {'n_atoms': 51, 'v_min': -10, 'v_max': 250}
filter-action: True
