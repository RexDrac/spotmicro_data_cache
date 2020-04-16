prioritized-exp-replay: True
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
state-dim: 18
loss-output-smooth-coeff: 1.0
critic-lr: 0.0003
expert-index: None
test-num: 4
interpolation: False
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
record-start-size: 10000.0
max-path-num: 20
Physics-frequency: 1000
squash-action: True
loss-entropy-coeff: 0.0
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
batch-size: 128
LLC-frequency: 500
HLC-frequency: 25
filter-torque: False
tau: 0.001
action-bounds: [[-0.5236 -2.666  -0.1    -0.5236 -2.666  -0.1    -0.5236 -2.666  -0.1
  -0.5236 -2.666  -0.1   ]
 [ 0.5236  1.548   2.09    0.5236  1.548   2.09    0.5236  1.548   2.09
   0.5236  1.548   2.09  ]]
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
env-id: HumanoidBalanceFilter-v0
actor-activation-fn: ['relu', 'relu', 'None']
actor-l2-reg: 0.0003
bullet-default-PD: False
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
train-step-num: 1
gamma: 0.995
imitation-weight: 1.0
actor-weight-decay: 1e-06
critic-weight-decay: 1e-06
expert-num: 4
reward-scale: 0.1
epoch-step-num: 5000000
epoch-num: 500
filter-action: True
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
gating-activation-fn: ['relu', 'relu', 'None']
max-step-num: 2500000000
max-episode-num: 5000000
task-weight: 0.0
rollout-step-num: 1
loss-output-diff-coeff: 0
loss-output-bound-coeff: 0.0
gating-layer-size: [32, 32]
render-eval: False
max-test-time: 10
critic-layer-size: [256, 256]
critic-l2-reg: 0.0003
n-step: 1
gating-index: None
total-step-num: 2500000000
joint-interpolation: True
replay-buffer-size: 1000000
replay-start-size: 10000
max-path-step: 5000
replay-ratio: 1
actor-layer-size: [256, 256]
action-dim: 12
categorical-distribution: {'n_atoms': 51, 'v_max': 250, 'v_min': -10}
actor-lr: 0.0003
critic-activation-fn: ['relu', 'relu', 'None']
max-train-time: 10
