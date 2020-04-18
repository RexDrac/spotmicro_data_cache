n-step: 1
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
loss-output-bound-coeff: 0.0
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
HLC-frequency: 25
imitation-weight: 0.5
interpolation: False
LLC-frequency: 500
max-train-time: 10
filter-torque: False
loss-output-diff-coeff: 0
tau: 0.001
loss-output-smooth-coeff: 0.5
critic-layer-size: [256, 256]
expert-index: None
action-dim: 12
max-path-step: 5000
bullet-default-PD: False
max-path-num: 20
actor-l2-reg: 0.0003
replay-start-size: 10000
dsr-gait-period: 0.6
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
rollout-step-num: 1
test-num: 4
train-step-num: 1
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
critic-l2-reg: 0.0003
categorical-distribution: {'n_atoms': 51, 'v_max': 250, 'v_min': -10}
render-eval: False
critic-lr: 0.0003
record-start-size: 10000.0
filter-action: True
max-test-time: 10
action-bounds: [[-0.5236 -2.666  -0.1    -0.5236 -2.666  -0.1    -0.5236 -2.666  -0.1
  -0.5236 -2.666  -0.1   ]
 [ 0.5236  1.548   2.09    0.5236  1.548   2.09    0.5236  1.548   2.09
   0.5236  1.548   2.09  ]]
squash-action: True
env-id: HumanoidBalanceFilter-v0
task-weight: 0.5
max-step-num: 2500000000
actor-activation-fn: ['relu', 'relu', 'None']
gating-index: None
actor-lr: 0.0003
total-step-num: 2500000000
critic-activation-fn: ['relu', 'relu', 'None']
critic-weight-decay: 1e-06
gamma: 0.955
gating-activation-fn: ['relu', 'relu', 'None']
actor-layer-size: [256, 256]
replay-ratio: 1
actor-weight-decay: 1e-06
replay-buffer-size: 1000000
dsr-gait-freq: 1.667
expert-num: 4
epoch-num: 500
joint-interpolation: True
reward-scale: 0.1
state-dim: 20
max-episode-num: 5000000
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
gating-layer-size: [32, 32]
prioritized-exp-replay: True
epoch-step-num: 5000000
loss-entropy-coeff: 0.0
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
batch-size: 128
Physics-frequency: 1000
