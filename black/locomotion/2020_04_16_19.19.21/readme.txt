dsr-gait-period: 0.6
epoch-num: 500
critic-activation-fn: ['relu', 'relu', 'None']
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
dsr-gait-freq: 1.667
filter-torque: False
record-start-size: 10000.0
imitation-weight: 0.5
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
HLC-frequency: 25
loss-output-bound-coeff: 0.0
loss-entropy-coeff: 0.0
epoch-step-num: 5000000
joint-interpolation: True
Physics-frequency: 1000
rollout-step-num: 1
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
loss-output-smooth-coeff: 0.5
total-step-num: 2500000000
task-weight: 0.5
action-dim: 12
max-path-step: 5000
squash-action: True
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
test-num: 4
filter-action: True
expert-num: 4
actor-weight-decay: 1e-06
expert-index: None
actor-layer-size: [256, 256]
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
categorical-distribution: {'v_max': 250, 'n_atoms': 51, 'v_min': -10}
replay-buffer-size: 1000000
train-step-num: 1
gamma: 0.955
actor-activation-fn: ['relu', 'relu', 'None']
max-episode-num: 5000000
tau: 0.001
actor-lr: 0.0003
gating-index: None
gating-layer-size: [32, 32]
action-bounds: [[-0.5236 -2.666  -0.1    -0.5236 -2.666  -0.1    -0.5236 -2.666  -0.1
  -0.5236 -2.666  -0.1   ]
 [ 0.5236  1.548   2.09    0.5236  1.548   2.09    0.5236  1.548   2.09
   0.5236  1.548   2.09  ]]
gating-activation-fn: ['relu', 'relu', 'None']
critic-l2-reg: 0.0003
bullet-default-PD: False
critic-lr: 0.0003
n-step: 1
env-id: HumanoidBalanceFilter-v0
prioritized-exp-replay: True
max-path-num: 20
critic-layer-size: [256, 256]
max-step-num: 2500000000
replay-start-size: 10000
max-test-time: 10
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
replay-ratio: 1
state-dim: 20
render-eval: False
LLC-frequency: 500
loss-output-diff-coeff: 0
batch-size: 128
actor-l2-reg: 0.0003
interpolation: False
max-train-time: 10
critic-weight-decay: 1e-06
reward-scale: 0.1
