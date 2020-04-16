actor-l2-reg: 0.0003
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
HLC-frequency: 25
epoch-num: 500
actor-layer-size: [256, 256]
env-id: HumanoidBalanceFilter-v0
interpolation: False
total-step-num: 2500000000
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
imitation-weight: 0.5
critic-layer-size: [256, 256]
categorical-distribution: {'v_min': -10, 'n_atoms': 51, 'v_max': 250}
gating-activation-fn: ['relu', 'relu', 'None']
dsr-gait-freq: 1.667
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
loss-output-smooth-coeff: 2.0
joint-interpolation: True
rollout-step-num: 1
reward-scale: 0.1
filter-torque: False
bullet-default-PD: False
expert-index: None
prioritized-exp-replay: True
train-step-num: 1
tau: 0.001
replay-ratio: 1
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
batch-size: 128
loss-output-diff-coeff: 0
max-step-num: 2500000000
state-dim: 20
n-step: 1
LLC-frequency: 500
actor-activation-fn: ['relu', 'relu', 'None']
actor-weight-decay: 1e-06
action-bounds: [[-0.5236 -2.666  -0.1    -0.5236 -2.666  -0.1    -0.5236 -2.666  -0.1
  -0.5236 -2.666  -0.1   ]
 [ 0.5236  1.548   2.09    0.5236  1.548   2.09    0.5236  1.548   2.09
   0.5236  1.548   2.09  ]]
record-start-size: 10000.0
squash-action: True
max-episode-num: 5000000
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
critic-lr: 0.0003
max-train-time: 10
epoch-step-num: 5000000
critic-weight-decay: 1e-06
loss-output-bound-coeff: 0.0
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
render-eval: False
dsr-gait-period: 0.6
test-num: 4
task-weight: 0.5
Physics-frequency: 1000
actor-lr: 0.0003
gating-layer-size: [32, 32]
max-test-time: 10
filter-action: True
action-dim: 12
max-path-step: 5000
gating-index: None
expert-num: 4
gamma: 0.955
replay-start-size: 10000
critic-l2-reg: 0.0003
replay-buffer-size: 1000000
critic-activation-fn: ['relu', 'relu', 'None']
loss-entropy-coeff: 0.0
max-path-num: 20
