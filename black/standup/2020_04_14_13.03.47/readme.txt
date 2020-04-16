actor-layer-size: [256, 256]
tau: 0.001
critic-layer-size: [256, 256]
action-dim: 12
epoch-step-num: 5000000
squash-action: True
loss-output-diff-coeff: 0
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
batch-size: 128
gating-activation-fn: ['relu', 'relu', 'None']
bullet-default-PD: False
reward-scale: 0.1
Physics-frequency: 1000
critic-weight-decay: 1e-06
replay-buffer-size: 1000000
gamma: 0.995
max-test-time: 10
actor-lr: 0.0003
replay-start-size: 10000
n-step: 1
loss-entropy-coeff: 0.0
record-start-size: 10000.0
rollout-step-num: 1
max-train-time: 10
state-dim: 18
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
filter-torque: False
HLC-frequency: 25
env-id: HumanoidBalanceFilter-v0
max-path-num: 20
prioritized-exp-replay: True
gating-layer-size: [32, 32]
epoch-num: 500
task-weight: 0.0
imitation-weight: 1.0
gating-index: None
max-path-step: 5000
critic-activation-fn: ['relu', 'relu', 'None']
loss-output-smooth-coeff: 1.0
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
train-step-num: 1
action-bounds: [[-0.5236 -2.666  -0.1    -0.5236 -2.666  -0.1    -0.5236 -2.666  -0.1
  -0.5236 -2.666  -0.1   ]
 [ 0.5236  1.548   2.09    0.5236  1.548   2.09    0.5236  1.548   2.09
   0.5236  1.548   2.09  ]]
test-num: 4
joint-interpolation: True
interpolation: False
critic-lr: 0.0003
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
loss-output-bound-coeff: 0.0
max-step-num: 2500000000
max-episode-num: 5000000
critic-l2-reg: 0.0003
filter-action: True
LLC-frequency: 500
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
categorical-distribution: {'n_atoms': 51, 'v_max': 250, 'v_min': -10}
expert-index: None
replay-ratio: 1
render-eval: False
actor-activation-fn: ['relu', 'relu', 'None']
total-step-num: 2500000000
expert-num: 4
actor-weight-decay: 1e-06
actor-l2-reg: 0.0003
