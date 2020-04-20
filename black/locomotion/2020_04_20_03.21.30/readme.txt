train-step-num: 1
max-test-time: 10
critic-l2-reg: 0.0003
task-weight: 0.5
epoch-num: 500
prioritized-exp-replay: True
replay-buffer-size: 1000000
critic-activation-fn: ['relu', 'relu', 'None']
gating-activation-fn: ['relu', 'relu', 'None']
joint-interpolation: True
critic-lr: 0.0003
critic-layer-size: [256, 256]
squash-action: True
loss-output-smooth-coeff: 1.0
gating-layer-size: [32, 32]
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
max-path-num: 20
max-train-time: 10
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
dsr-gait-freq: 1.667
max-path-step: 5000
n-step: 1
reward-scale: 0.1
actor-layer-size: [256, 256]
actor-lr: 0.0003
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
loss-output-bound-coeff: 0.0
critic-weight-decay: 1e-06
actor-l2-reg: 0.0003
actor-activation-fn: ['relu', 'relu', 'None']
state-dim: 20
batch-size: 128
replay-start-size: 10000
total-step-num: 2500000000
gamma: 0.955
render-eval: False
filter-torque: False
bullet-default-PD: False
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
categorical-distribution: {'n_atoms': 51, 'v_min': -10, 'v_max': 250}
loss-entropy-coeff: 0.0
max-episode-num: 5000000
expert-num: 4
Physics-frequency: 1000
max-step-num: 2500000000
rollout-step-num: 1
imitation-weight: 0.5
dsr-gait-period: 0.6
LLC-frequency: 500
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
epoch-step-num: 5000000
gating-index: None
expert-index: None
action-dim: 12
loss-output-diff-coeff: 0
HLC-frequency: 25
record-start-size: 10000.0
interpolation: False
test-num: 4
replay-ratio: 1
tau: 0.001
env-id: HumanoidBalanceFilter-v0
filter-action: True
actor-weight-decay: 1e-06
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
action-bounds: [[-0.5236 -2.666  -0.1    -0.5236 -2.666  -0.1    -0.5236 -2.666  -0.1
  -0.5236 -2.666  -0.1   ]
 [ 0.5236  1.548   2.09    0.5236  1.548   2.09    0.5236  1.548   2.09
   0.5236  1.548   2.09  ]]
