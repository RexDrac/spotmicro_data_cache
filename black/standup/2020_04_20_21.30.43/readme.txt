loss-output-bound-coeff: 0.0
critic-layer-size: [256, 256]
tau: 0.001
imitation-weight: 1.0
max-path-num: 20
loss-output-diff-coeff: 0
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
render-eval: False
reward-scale: 0.1
rollout-step-num: 1
n-step: 1
loss-output-smooth-coeff: 1.0
critic-l2-reg: 0.0003
HLC-frequency: 25
actor-activation-fn: ['relu', 'relu', 'None']
filter-action: True
critic-activation-fn: ['relu', 'relu', 'None']
total-step-num: 2500000000
test-num: 4
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
replay-start-size: 10000
squash-action: True
interpolation: False
actor-weight-decay: 1e-06
gamma: 0.995
prioritized-exp-replay: True
replay-ratio: 1
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
critic-weight-decay: 1e-06
critic-lr: 0.0003
state-dim: 18
env-id: HumanoidBalanceFilter-v0
max-train-time: 10
actor-layer-size: [256, 256]
actor-l2-reg: 0.0003
bullet-default-PD: False
action-dim: 12
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
LLC-frequency: 500
actor-lr: 0.0003
replay-buffer-size: 1000000
action-bounds: [[-0.5236 -2.666  -0.1    -0.5236 -2.666  -0.1    -0.5236 -2.666  -0.1
  -0.5236 -2.666  -0.1   ]
 [ 0.5236  1.548   2.09    0.5236  1.548   2.09    0.5236  1.548   2.09
   0.5236  1.548   2.09  ]]
max-episode-num: 5000000
joint-interpolation: True
max-path-step: 5000
max-step-num: 2500000000
categorical-distribution: {'v_min': -10, 'n_atoms': 51, 'v_max': 250}
record-start-size: 10000.0
batch-size: 128
expert-num: 4
gating-index: None
train-step-num: 1
gating-activation-fn: ['relu', 'relu', 'None']
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
max-test-time: 10
epoch-step-num: 5000000
task-weight: 0.0
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
filter-torque: False
epoch-num: 500
Physics-frequency: 1000
loss-entropy-coeff: 0.0
expert-index: None
gating-layer-size: [32, 32]
