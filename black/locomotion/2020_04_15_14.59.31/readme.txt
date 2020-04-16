env-id: HumanoidBalanceFilter-v0
joint-interpolation: True
batch-size: 128
loss-entropy-coeff: 0.0
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
record-start-size: 10000.0
loss-output-bound-coeff: 0.0
critic-layer-size: [256, 256]
bullet-default-PD: False
max-episode-num: 5000000
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
gating-layer-size: [32, 32]
max-train-time: 10
replay-buffer-size: 1000000
HLC-frequency: 25
train-step-num: 1
critic-lr: 0.0003
max-path-step: 5000
epoch-num: 500
actor-activation-fn: ['relu', 'relu', 'None']
n-step: 1
replay-start-size: 10000
action-dim: 12
LLC-frequency: 500
critic-activation-fn: ['relu', 'relu', 'None']
max-path-num: 20
Physics-frequency: 1000
test-num: 4
tau: 0.001
loss-output-smooth-coeff: 0.1
loss-output-diff-coeff: 0
critic-weight-decay: 1e-06
actor-lr: 0.0003
filter-torque: False
dsr-gait-period: 0.6
task-weight: 0.5
gating-index: None
prioritized-exp-replay: True
actor-l2-reg: 0.0003
max-step-num: 2500000000
actor-weight-decay: 1e-06
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
gating-activation-fn: ['relu', 'relu', 'None']
interpolation: False
imitation-weight: 0.5
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
render-eval: False
total-step-num: 2500000000
dsr-gait-freq: 1.667
actor-layer-size: [256, 256]
max-test-time: 10
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
gamma: 0.955
critic-l2-reg: 0.0003
state-dim: 20
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
expert-num: 4
squash-action: True
replay-ratio: 1
expert-index: None
reward-scale: 0.1
categorical-distribution: {'v_min': -10, 'n_atoms': 51, 'v_max': 250}
filter-action: True
rollout-step-num: 1
action-bounds: [[-0.5236 -2.666  -0.1    -0.5236 -2.666  -0.1    -0.5236 -2.666  -0.1
  -0.5236 -2.666  -0.1   ]
 [ 0.5236  1.548   2.09    0.5236  1.548   2.09    0.5236  1.548   2.09
   0.5236  1.548   2.09  ]]
epoch-step-num: 5000000
