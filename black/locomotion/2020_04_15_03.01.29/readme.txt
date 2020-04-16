filter-torque: False
prioritized-exp-replay: True
train-step-num: 1
actor-weight-decay: 1e-06
render-eval: False
expert-index: None
total-step-num: 2500000000
max-path-step: 5000
max-episode-num: 5000000
actor-lr: 0.0003
replay-ratio: 1
critic-l2-reg: 0.0003
replay-buffer-size: 1000000
filter-action: True
critic-activation-fn: ['relu', 'relu', 'None']
loss-output-smooth-coeff: 1.0
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
max-test-time: 10
max-step-num: 2500000000
epoch-step-num: 5000000
categorical-distribution: {'v_max': 250, 'n_atoms': 51, 'v_min': -10}
actor-l2-reg: 0.0003
action-bounds: [[-0.5236 -2.666  -0.1    -0.5236 -2.666  -0.1    -0.5236 -2.666  -0.1
  -0.5236 -2.666  -0.1   ]
 [ 0.5236  1.548   2.09    0.5236  1.548   2.09    0.5236  1.548   2.09
   0.5236  1.548   2.09  ]]
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
expert-num: 4
critic-weight-decay: 1e-06
LLC-frequency: 500
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
dsr-gait-freq: 1.667
HLC-frequency: 25
loss-output-diff-coeff: 0
reward-scale: 0.1
gating-index: None
actor-layer-size: [256, 256]
gamma: 0.955
test-num: 4
gating-activation-fn: ['relu', 'relu', 'None']
squash-action: True
dsr-gait-period: 0.6
batch-size: 128
loss-entropy-coeff: 0.0
env-id: HumanoidBalanceFilter-v0
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
bullet-default-PD: False
Physics-frequency: 1000
actor-activation-fn: ['relu', 'relu', 'None']
max-train-time: 10
rollout-step-num: 1
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
max-path-num: 20
epoch-num: 500
imitation-weight: 0.5
action-dim: 12
gating-layer-size: [32, 32]
record-start-size: 10000.0
joint-interpolation: True
state-dim: 20
replay-start-size: 10000
interpolation: False
loss-output-bound-coeff: 0.0
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
task-weight: 0.5
n-step: 1
tau: 0.001
critic-layer-size: [256, 256]
critic-lr: 0.0003
