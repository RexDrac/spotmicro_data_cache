dsr-gait-period: 0.6
critic-activation-fn: ['relu', 'relu', 'None']
critic-lr: 0.0003
max-path-step: 5000
gamma: 0.955
reward-scale: 0.1
joint-interpolation: True
categorical-distribution: {'n_atoms': 51, 'v_max': 250, 'v_min': -10}
HLC-frequency: 25
gating-activation-fn: ['relu', 'relu', 'None']
expert-index: None
epoch-num: 500
expert-num: 4
n-step: 1
action-dim: 12
action-bounds: [[-0.5236 -2.666  -0.1    -0.5236 -2.666  -0.1    -0.5236 -2.666  -0.1
  -0.5236 -2.666  -0.1   ]
 [ 0.5236  1.548   2.09    0.5236  1.548   2.09    0.5236  1.548   2.09
   0.5236  1.548   2.09  ]]
epoch-step-num: 5000000
loss-output-diff-coeff: 0
replay-ratio: 1
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
total-step-num: 2500000000
prioritized-exp-replay: True
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
LLC-frequency: 500
state-dim: 20
filter-torque: False
critic-l2-reg: 0.0003
critic-layer-size: [256, 256]
max-episode-num: 5000000
critic-weight-decay: 1e-06
record-start-size: 10000.0
gating-layer-size: [32, 32]
replay-start-size: 10000
max-train-time: 10
replay-buffer-size: 1000000
imitation-weight: 0.5
interpolation: False
max-step-num: 2500000000
actor-layer-size: [256, 256]
max-test-time: 10
max-path-num: 20
test-num: 4
loss-output-bound-coeff: 0.0
train-step-num: 1
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
loss-output-smooth-coeff: 0.5
batch-size: 128
actor-l2-reg: 0.0003
actor-weight-decay: 1e-06
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
env-id: HumanoidBalanceFilter-v0
actor-activation-fn: ['relu', 'relu', 'None']
tau: 0.001
task-weight: 0.5
dsr-gait-freq: 1.667
rollout-step-num: 1
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
actor-lr: 0.0003
Physics-frequency: 1000
squash-action: True
bullet-default-PD: False
render-eval: False
gating-index: None
filter-action: True
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
loss-entropy-coeff: 0.0
