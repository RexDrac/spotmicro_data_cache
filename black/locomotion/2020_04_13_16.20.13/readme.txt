epoch-step-num: 5000000
interpolation: False
train-step-num: 1
filter-torque: False
critic-lr: 0.0003
critic-activation-fn: ['relu', 'relu', 'None']
replay-ratio: 1
task-weight: 0.5
test-num: 4
replay-buffer-size: 1000000
rollout-step-num: 1
tau: 0.001
n-step: 1
joint-interpolation: True
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
record-start-size: 10000.0
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
expert-num: 4
max-train-time: 10
critic-weight-decay: 1e-06
LLC-frequency: 500
actor-layer-size: [256, 256]
filter-action: True
max-path-step: 5000
max-step-num: 2500000000
dsr-gait-period: 0.6
loss-output-smooth-coeff: 2.0
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
expert-index: None
critic-layer-size: [256, 256]
state-dim: 20
replay-start-size: 10000
Physics-frequency: 1000
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
prioritized-exp-replay: True
dsr-gait-freq: 1.667
imitation-weight: 0.5
max-path-num: 20
actor-weight-decay: 1e-06
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
loss-output-bound-coeff: 0.0
squash-action: True
batch-size: 128
loss-entropy-coeff: 0.0
loss-output-diff-coeff: 0
gating-index: None
gating-layer-size: [32, 32]
actor-activation-fn: ['relu', 'relu', 'None']
categorical-distribution: {'n_atoms': 51, 'v_max': 250, 'v_min': -10}
actor-l2-reg: 0.0003
env-id: HumanoidBalanceFilter-v0
gamma: 0.955
actor-lr: 0.0003
render-eval: False
action-bounds: [[-0.5236 -2.666  -0.1    -0.5236 -2.666  -0.1    -0.5236 -2.666  -0.1
  -0.5236 -2.666  -0.1   ]
 [ 0.5236  1.548   2.09    0.5236  1.548   2.09    0.5236  1.548   2.09
   0.5236  1.548   2.09  ]]
total-step-num: 2500000000
HLC-frequency: 25
gating-activation-fn: ['relu', 'relu', 'None']
max-episode-num: 5000000
action-dim: 12
bullet-default-PD: False
critic-l2-reg: 0.0003
max-test-time: 10
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
reward-scale: 0.1
epoch-num: 500
