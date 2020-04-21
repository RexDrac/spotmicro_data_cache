actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
max-test-time: 10
batch-size: 128
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
replay-ratio: 1
imitation-weight: 1.0
critic-layer-size: [256, 256]
critic-weight-decay: 1e-06
replay-buffer-size: 1000000
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
LLC-frequency: 500
epoch-step-num: 5000000
render-eval: False
action-bounds: [[-0.5236 -2.666  -0.1    -0.5236 -2.666  -0.1    -0.5236 -2.666  -0.1
  -0.5236 -2.666  -0.1   ]
 [ 0.5236  1.548   2.09    0.5236  1.548   2.09    0.5236  1.548   2.09
   0.5236  1.548   2.09  ]]
HLC-frequency: 25
actor-activation-fn: ['relu', 'relu', 'None']
loss-entropy-coeff: 0.0
state-dim: 18
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
max-episode-num: 5000000
categorical-distribution: {'v_max': 250, 'v_min': -10, 'n_atoms': 51}
expert-index: None
loss-output-bound-coeff: 0.0
actor-layer-size: [256, 256]
max-step-num: 2500000000
epoch-num: 500
actor-lr: 0.0003
gating-index: None
filter-torque: False
actor-weight-decay: 1e-06
max-path-num: 20
max-path-step: 5000
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
env-id: HumanoidBalanceFilter-v0
critic-activation-fn: ['relu', 'relu', 'None']
loss-output-diff-coeff: 0
tau: 0.001
bullet-default-PD: False
actor-l2-reg: 0.0003
joint-interpolation: True
rollout-step-num: 1
test-num: 4
gating-layer-size: [32, 32]
gating-activation-fn: ['relu', 'relu', 'None']
max-train-time: 10
prioritized-exp-replay: True
n-step: 1
expert-num: 4
squash-action: True
record-start-size: 10000.0
critic-lr: 0.0003
replay-start-size: 10000
Physics-frequency: 1000
filter-action: True
critic-l2-reg: 0.0003
reward-scale: 0.1
train-step-num: 1
action-dim: 12
task-weight: 0.0
loss-output-smooth-coeff: 1.0
interpolation: False
gamma: 0.995
total-step-num: 2500000000
