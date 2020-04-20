loss-output-smooth-coeff: 0.5
max-test-time: 10
LLC-frequency: 500
prioritized-exp-replay: True
render-eval: False
HLC-frequency: 25
gating-index: None
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
env-id: HumanoidBalanceFilter-v0
dsr-gait-period: 0.6
interpolation: False
actor-activation-fn: ['relu', 'relu', 'None']
max-path-step: 5000
expert-index: None
expert-num: 4
loss-output-diff-coeff: 0
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
action-bounds: [[-0.5236 -2.666  -0.1    -0.5236 -2.666  -0.1    -0.5236 -2.666  -0.1
  -0.5236 -2.666  -0.1   ]
 [ 0.5236  1.548   2.09    0.5236  1.548   2.09    0.5236  1.548   2.09
   0.5236  1.548   2.09  ]]
gating-activation-fn: ['relu', 'relu', 'None']
actor-weight-decay: 1e-06
reward-scale: 0.1
imitation-weight: 0.5
max-episode-num: 5000000
replay-ratio: 1
state-dim: 20
rollout-step-num: 1
critic-lr: 0.0003
max-train-time: 10
max-step-num: 2500000000
batch-size: 128
max-path-num: 20
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
critic-layer-size: [256, 256]
record-start-size: 10000.0
filter-action: True
loss-output-bound-coeff: 0.0
critic-weight-decay: 1e-06
epoch-step-num: 5000000
replay-start-size: 10000
actor-lr: 0.0003
joint-interpolation: True
squash-action: True
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
action-dim: 12
filter-torque: False
task-weight: 0.5
replay-buffer-size: 1000000
tau: 0.001
n-step: 1
train-step-num: 1
Physics-frequency: 1000
categorical-distribution: {'v_min': -10, 'n_atoms': 51, 'v_max': 250}
actor-layer-size: [256, 256]
loss-entropy-coeff: 0.0
gating-layer-size: [32, 32]
critic-l2-reg: 0.0003
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
gamma: 0.955
actor-l2-reg: 0.0003
total-step-num: 2500000000
dsr-gait-freq: 1.667
critic-activation-fn: ['relu', 'relu', 'None']
bullet-default-PD: False
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
epoch-num: 500
test-num: 4
