task-weight: 0.5
bullet-default-PD: False
gating-activation-fn: ['relu', 'relu', 'None']
max-train-time: 10
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
actor-layer-size: [256, 256]
state-dim: 20
critic-activation-fn: ['relu', 'relu', 'None']
filter-torque: False
test-num: 4
rollout-step-num: 1
critic-weight-decay: 1e-06
HLC-frequency: 25
n-step: 1
prioritized-exp-replay: True
epoch-step-num: 5000000
actor-l2-reg: 0.0003
replay-start-size: 10000
max-step-num: 2500000000
squash-action: True
actor-lr: 0.0003
dsr-gait-period: 0.6
gating-index: None
replay-ratio: 1
Physics-frequency: 1000
batch-size: 128
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
max-test-time: 10
tau: 0.001
actor-weight-decay: 1e-06
max-path-step: 5000
action-bounds: [[-0.5236 -2.666  -0.1    -0.5236 -2.666  -0.1    -0.5236 -2.666  -0.1
  -0.5236 -2.666  -0.1   ]
 [ 0.5236  1.548   2.09    0.5236  1.548   2.09    0.5236  1.548   2.09
   0.5236  1.548   2.09  ]]
loss-entropy-coeff: 0.0
imitation-weight: 0.5
env-id: HumanoidBalanceFilter-v0
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
max-episode-num: 5000000
gating-layer-size: [32, 32]
loss-output-bound-coeff: 0.0
train-step-num: 1
max-path-num: 20
replay-buffer-size: 1000000
expert-num: 4
epoch-num: 500
expert-index: None
loss-output-smooth-coeff: 2.0
dsr-gait-freq: 1.667
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
gamma: 0.955
render-eval: False
categorical-distribution: {'n_atoms': 51, 'v_min': -10, 'v_max': 250}
critic-lr: 0.0003
joint-interpolation: True
critic-layer-size: [256, 256]
interpolation: False
actor-activation-fn: ['relu', 'relu', 'None']
LLC-frequency: 500
critic-l2-reg: 0.0003
filter-action: True
loss-output-diff-coeff: 0
reward-scale: 0.1
action-dim: 12
record-start-size: 10000.0
total-step-num: 2500000000
