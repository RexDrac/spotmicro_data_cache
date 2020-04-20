actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
max-path-step: 5000
max-episode-num: 5000000
categorical-distribution: {'n_atoms': 51, 'v_max': 250, 'v_min': -10}
loss-entropy-coeff: 0.0
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
train-step-num: 1
critic-weight-decay: 1e-06
gating-index: None
action-dim: 12
tau: 0.001
expert-index: None
actor-activation-fn: ['relu', 'relu', 'None']
imitation-weight: 0.5
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
critic-layer-size: [256, 256]
dsr-gait-period: 0.6
task-weight: 0.5
critic-lr: 0.0003
replay-buffer-size: 1000000
rollout-step-num: 1
gating-activation-fn: ['relu', 'relu', 'None']
total-step-num: 2500000000
prioritized-exp-replay: True
record-start-size: 10000.0
max-path-num: 20
joint-interpolation: True
loss-output-diff-coeff: 0
HLC-frequency: 25
Physics-frequency: 1000
epoch-num: 500
actor-l2-reg: 0.0003
max-train-time: 10
replay-ratio: 1
gating-layer-size: [32, 32]
LLC-frequency: 500
actor-weight-decay: 1e-06
critic-activation-fn: ['relu', 'relu', 'None']
loss-output-bound-coeff: 0.0
actor-layer-size: [256, 256]
bullet-default-PD: False
batch-size: 128
gamma: 0.955
action-bounds: [[-0.5236 -2.666  -0.1    -0.5236 -2.666  -0.1    -0.5236 -2.666  -0.1
  -0.5236 -2.666  -0.1   ]
 [ 0.5236  1.548   2.09    0.5236  1.548   2.09    0.5236  1.548   2.09
   0.5236  1.548   2.09  ]]
filter-torque: False
filter-action: True
max-test-time: 10
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
test-num: 4
max-step-num: 2500000000
n-step: 1
expert-num: 4
interpolation: False
reward-scale: 0.1
critic-l2-reg: 0.0003
render-eval: False
state-dim: 20
replay-start-size: 10000
dsr-gait-freq: 1.667
actor-lr: 0.0003
epoch-step-num: 5000000
squash-action: True
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
loss-output-smooth-coeff: 0.5
env-id: HumanoidBalanceFilter-v0
