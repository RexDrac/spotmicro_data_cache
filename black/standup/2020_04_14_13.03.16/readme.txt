batch-size: 128
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
max-path-num: 20
critic-activation-fn: ['relu', 'relu', 'None']
actor-lr: 0.0003
joint-interpolation: True
LLC-frequency: 500
action-dim: 12
imitation-weight: 1.0
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
tau: 0.001
expert-index: None
HLC-frequency: 25
record-start-size: 10000.0
env-id: HumanoidBalanceFilter-v0
Physics-frequency: 1000
max-train-time: 10
replay-start-size: 10000
epoch-num: 500
critic-layer-size: [256, 256]
squash-action: True
filter-action: True
gating-activation-fn: ['relu', 'relu', 'None']
loss-output-smooth-coeff: 1.0
expert-num: 4
test-num: 4
gamma: 0.995
render-eval: False
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
state-dim: 18
actor-l2-reg: 0.0003
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
replay-buffer-size: 1000000
replay-ratio: 1
max-step-num: 2500000000
reward-scale: 0.1
filter-torque: False
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
categorical-distribution: {'v_max': 250, 'v_min': -10, 'n_atoms': 51}
loss-output-bound-coeff: 0.0
actor-layer-size: [256, 256]
action-bounds: [[-0.5236 -2.666  -0.1    -0.5236 -2.666  -0.1    -0.5236 -2.666  -0.1
  -0.5236 -2.666  -0.1   ]
 [ 0.5236  1.548   2.09    0.5236  1.548   2.09    0.5236  1.548   2.09
   0.5236  1.548   2.09  ]]
rollout-step-num: 1
train-step-num: 1
critic-l2-reg: 0.0003
prioritized-exp-replay: True
bullet-default-PD: False
gating-index: None
interpolation: False
actor-weight-decay: 1e-06
n-step: 1
task-weight: 0.0
epoch-step-num: 5000000
max-test-time: 10
loss-output-diff-coeff: 0
loss-entropy-coeff: 0.0
max-episode-num: 5000000
actor-activation-fn: ['relu', 'relu', 'None']
max-path-step: 5000
gating-layer-size: [32, 32]
critic-weight-decay: 1e-06
total-step-num: 2500000000
critic-lr: 0.0003
