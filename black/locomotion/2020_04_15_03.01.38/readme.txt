actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
n-step: 1
actor-layer-size: [256, 256]
actor-weight-decay: 1e-06
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
interpolation: False
actor-lr: 0.0003
dsr-gait-freq: 1.667
critic-l2-reg: 0.0003
Physics-frequency: 1000
filter-torque: False
action-dim: 12
gating-activation-fn: ['relu', 'relu', 'None']
categorical-distribution: {'v_max': 250, 'n_atoms': 51, 'v_min': -10}
epoch-num: 500
task-weight: 0.5
replay-ratio: 1
max-path-num: 20
gating-layer-size: [32, 32]
gamma: 0.955
dsr-gait-period: 0.6
max-test-time: 10
total-step-num: 2500000000
tau: 0.001
prioritized-exp-replay: True
action-bounds: [[-0.5236 -2.666  -0.1    -0.5236 -2.666  -0.1    -0.5236 -2.666  -0.1
  -0.5236 -2.666  -0.1   ]
 [ 0.5236  1.548   2.09    0.5236  1.548   2.09    0.5236  1.548   2.09
   0.5236  1.548   2.09  ]]
loss-output-smooth-coeff: 1.0
env-id: HumanoidBalanceFilter-v0
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
rollout-step-num: 1
loss-entropy-coeff: 0.0
loss-output-bound-coeff: 0.0
filter-action: True
gating-index: None
LLC-frequency: 500
loss-output-diff-coeff: 0
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
test-num: 4
epoch-step-num: 5000000
batch-size: 128
squash-action: True
max-episode-num: 5000000
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
replay-buffer-size: 1000000
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
state-dim: 20
max-train-time: 10
critic-layer-size: [256, 256]
imitation-weight: 0.5
max-path-step: 5000
record-start-size: 10000.0
replay-start-size: 10000
actor-l2-reg: 0.0003
HLC-frequency: 25
expert-num: 4
joint-interpolation: True
expert-index: None
reward-scale: 0.1
critic-weight-decay: 1e-06
max-step-num: 2500000000
critic-lr: 0.0003
bullet-default-PD: False
critic-activation-fn: ['relu', 'relu', 'None']
train-step-num: 1
render-eval: False
actor-activation-fn: ['relu', 'relu', 'None']
