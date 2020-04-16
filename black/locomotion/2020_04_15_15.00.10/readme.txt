actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
dsr-gait-freq: 1.667
actor-l2-reg: 0.0003
actor-weight-decay: 1e-06
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
action-dim: 12
actor-lr: 0.0003
joint-interpolation: True
squash-action: True
record-start-size: 10000.0
filter-torque: False
train-step-num: 1
loss-output-bound-coeff: 0.0
replay-ratio: 1
n-step: 1
max-episode-num: 5000000
critic-weight-decay: 1e-06
task-weight: 0.5
env-id: HumanoidBalanceFilter-v0
total-step-num: 2500000000
max-step-num: 2500000000
Physics-frequency: 1000
gamma: 0.955
loss-output-diff-coeff: 0
expert-index: None
actor-activation-fn: ['relu', 'relu', 'None']
categorical-distribution: {'v_min': -10, 'n_atoms': 51, 'v_max': 250}
batch-size: 128
max-path-step: 5000
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
prioritized-exp-replay: True
interpolation: False
expert-num: 4
test-num: 4
bullet-default-PD: False
state-dim: 20
critic-lr: 0.0003
render-eval: False
critic-l2-reg: 0.0003
replay-buffer-size: 1000000
imitation-weight: 0.5
epoch-num: 500
rollout-step-num: 1
tau: 0.001
gating-layer-size: [32, 32]
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
critic-layer-size: [256, 256]
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
actor-layer-size: [256, 256]
replay-start-size: 10000
dsr-gait-period: 0.6
max-path-num: 20
filter-action: True
max-train-time: 10
epoch-step-num: 5000000
reward-scale: 0.1
gating-index: None
HLC-frequency: 25
critic-activation-fn: ['relu', 'relu', 'None']
loss-entropy-coeff: 0.0
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
max-test-time: 10
gating-activation-fn: ['relu', 'relu', 'None']
loss-output-smooth-coeff: 0.1
action-bounds: [[-0.5236 -2.666  -0.1    -0.5236 -2.666  -0.1    -0.5236 -2.666  -0.1
  -0.5236 -2.666  -0.1   ]
 [ 0.5236  1.548   2.09    0.5236  1.548   2.09    0.5236  1.548   2.09
   0.5236  1.548   2.09  ]]
LLC-frequency: 500
