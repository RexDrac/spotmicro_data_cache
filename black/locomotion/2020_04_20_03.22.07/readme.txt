gating-activation-fn: ['relu', 'relu', 'None']
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
n-step: 1
gating-layer-size: [32, 32]
expert-num: 4
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
reward-scale: 0.1
max-episode-num: 5000000
total-step-num: 2500000000
replay-ratio: 1
epoch-num: 500
expert-index: None
actor-layer-size: [256, 256]
bullet-default-PD: False
loss-output-bound-coeff: 0.0
critic-weight-decay: 1e-06
max-train-time: 10
rollout-step-num: 1
interpolation: False
max-test-time: 10
actor-activation-fn: ['relu', 'relu', 'None']
env-id: HumanoidBalanceFilter-v0
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
filter-action: True
task-weight: 0.5
actor-l2-reg: 0.0003
actor-weight-decay: 1e-06
max-path-step: 5000
gating-index: None
LLC-frequency: 500
action-dim: 12
critic-lr: 0.0003
filter-torque: False
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
joint-interpolation: True
replay-start-size: 10000
tau: 0.001
HLC-frequency: 25
dsr-gait-period: 0.6
max-path-num: 20
train-step-num: 1
action-bounds: [[-0.5236 -2.666  -0.1    -0.5236 -2.666  -0.1    -0.5236 -2.666  -0.1
  -0.5236 -2.666  -0.1   ]
 [ 0.5236  1.548   2.09    0.5236  1.548   2.09    0.5236  1.548   2.09
   0.5236  1.548   2.09  ]]
prioritized-exp-replay: True
test-num: 4
categorical-distribution: {'n_atoms': 51, 'v_max': 250, 'v_min': -10}
replay-buffer-size: 1000000
loss-output-smooth-coeff: 1.0
critic-l2-reg: 0.0003
state-dim: 20
critic-activation-fn: ['relu', 'relu', 'None']
dsr-gait-freq: 1.667
critic-layer-size: [256, 256]
max-step-num: 2500000000
gamma: 0.955
imitation-weight: 0.5
Physics-frequency: 1000
render-eval: False
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-lr: 0.0003
squash-action: True
loss-entropy-coeff: 0.0
epoch-step-num: 5000000
record-start-size: 10000.0
loss-output-diff-coeff: 0
batch-size: 128
