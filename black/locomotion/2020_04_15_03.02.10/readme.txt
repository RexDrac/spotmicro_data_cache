LLC-frequency: 500
test-num: 4
replay-ratio: 1
dsr-gait-freq: 1.667
gating-index: None
epoch-step-num: 5000000
env-id: HumanoidBalanceFilter-v0
max-train-time: 10
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
critic-layer-size: [256, 256]
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
joint-interpolation: True
rollout-step-num: 1
action-dim: 12
dsr-gait-period: 0.6
categorical-distribution: {'v_max': 250, 'n_atoms': 51, 'v_min': -10}
max-path-num: 20
n-step: 1
filter-action: True
train-step-num: 1
actor-activation-fn: ['relu', 'relu', 'None']
Physics-frequency: 1000
actor-layer-size: [256, 256]
interpolation: False
bullet-default-PD: False
loss-output-smooth-coeff: 1.0
imitation-weight: 0.5
replay-start-size: 10000
tau: 0.001
loss-output-diff-coeff: 0
state-dim: 20
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
render-eval: False
batch-size: 128
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
max-step-num: 2500000000
expert-num: 4
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
epoch-num: 500
critic-weight-decay: 1e-06
filter-torque: False
gamma: 0.955
prioritized-exp-replay: True
expert-index: None
gating-activation-fn: ['relu', 'relu', 'None']
actor-l2-reg: 0.0003
total-step-num: 2500000000
gating-layer-size: [32, 32]
actor-lr: 0.0003
record-start-size: 10000.0
HLC-frequency: 25
critic-l2-reg: 0.0003
max-test-time: 10
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
squash-action: True
task-weight: 0.5
loss-entropy-coeff: 0.0
critic-activation-fn: ['relu', 'relu', 'None']
loss-output-bound-coeff: 0.0
action-bounds: [[-0.5236 -2.666  -0.1    -0.5236 -2.666  -0.1    -0.5236 -2.666  -0.1
  -0.5236 -2.666  -0.1   ]
 [ 0.5236  1.548   2.09    0.5236  1.548   2.09    0.5236  1.548   2.09
   0.5236  1.548   2.09  ]]
replay-buffer-size: 1000000
max-path-step: 5000
actor-weight-decay: 1e-06
critic-lr: 0.0003
max-episode-num: 5000000
reward-scale: 0.1
