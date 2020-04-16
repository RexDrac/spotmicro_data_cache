imitation-weight: 0.5
gating-activation-fn: ['relu', 'relu', 'None']
critic-lr: 0.0003
test-num: 4
total-step-num: 2500000000
replay-ratio: 1
replay-start-size: 10000
max-step-num: 2500000000
critic-l2-reg: 0.0003
rollout-step-num: 1
joint-interpolation: True
filter-action: True
expert-num: 4
gating-layer-size: [32, 32]
dsr-gait-period: 0.6
render-eval: False
dsr-gait-freq: 1.667
squash-action: True
task-weight: 0.5
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
critic-weight-decay: 1e-06
loss-output-smooth-coeff: 2.0
n-step: 1
gamma: 0.955
env-id: HumanoidBalanceFilter-v0
Physics-frequency: 1000
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
actor-activation-fn: ['relu', 'relu', 'None']
critic-activation-fn: ['relu', 'relu', 'None']
tau: 0.001
max-path-num: 20
train-step-num: 1
state-dim: 20
epoch-num: 500
filter-torque: False
critic-layer-size: [256, 256]
action-dim: 12
batch-size: 128
LLC-frequency: 500
max-train-time: 10
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
reward-scale: 0.1
prioritized-exp-replay: True
actor-layer-size: [256, 256]
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
loss-entropy-coeff: 0.0
loss-output-bound-coeff: 0.0
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
categorical-distribution: {'n_atoms': 51, 'v_min': -10, 'v_max': 250}
actor-weight-decay: 1e-06
replay-buffer-size: 1000000
actor-lr: 0.0003
bullet-default-PD: False
actor-l2-reg: 0.0003
expert-index: None
max-test-time: 10
record-start-size: 10000.0
loss-output-diff-coeff: 0
HLC-frequency: 25
max-path-step: 5000
epoch-step-num: 5000000
action-bounds: [[-0.5236 -2.666  -0.1    -0.5236 -2.666  -0.1    -0.5236 -2.666  -0.1
  -0.5236 -2.666  -0.1   ]
 [ 0.5236  1.548   2.09    0.5236  1.548   2.09    0.5236  1.548   2.09
   0.5236  1.548   2.09  ]]
gating-index: None
interpolation: False
max-episode-num: 5000000
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
