actor-lr: 0.0003
prioritized-exp-replay: True
replay-start-size: 10000
max-episode-num: 5000000
actor-activation-fn: ['relu', 'relu', 'None']
LLC-frequency: 500
critic-weight-decay: 1e-06
actor-layer-size: [256, 256]
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
action-dim: 12
task-weight: 0.5
loss-output-diff-coeff: 0
dsr-gait-freq: 1.667
n-step: 1
epoch-num: 500
gating-activation-fn: ['relu', 'relu', 'None']
bullet-default-PD: False
render-eval: False
tau: 0.001
critic-lr: 0.0003
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
replay-ratio: 1
state-dim: 20
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
gating-index: None
critic-l2-reg: 0.0003
critic-activation-fn: ['relu', 'relu', 'None']
record-start-size: 10000.0
gating-layer-size: [32, 32]
Physics-frequency: 1000
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-weight-decay: 1e-06
HLC-frequency: 25
env-id: HumanoidBalanceFilter-v0
total-step-num: 2500000000
max-path-num: 20
test-num: 4
batch-size: 128
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
actor-l2-reg: 0.0003
max-train-time: 10
epoch-step-num: 5000000
rollout-step-num: 1
categorical-distribution: {'n_atoms': 51, 'v_min': -10, 'v_max': 250}
filter-action: True
max-test-time: 10
squash-action: True
dsr-gait-period: 0.6
loss-output-bound-coeff: 0.0
expert-index: None
loss-entropy-coeff: 0.0
reward-scale: 0.1
max-path-step: 5000
replay-buffer-size: 1000000
gamma: 0.955
critic-layer-size: [256, 256]
expert-num: 4
filter-torque: False
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
loss-output-smooth-coeff: 1.0
action-bounds: [[-0.5236 -2.666  -0.1    -0.5236 -2.666  -0.1    -0.5236 -2.666  -0.1
  -0.5236 -2.666  -0.1   ]
 [ 0.5236  1.548   2.09    0.5236  1.548   2.09    0.5236  1.548   2.09
   0.5236  1.548   2.09  ]]
train-step-num: 1
max-step-num: 2500000000
joint-interpolation: True
imitation-weight: 0.5
interpolation: False
