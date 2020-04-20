render-eval: False
prioritized-exp-replay: True
Physics-frequency: 1000
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
max-path-num: 20
loss-output-diff-coeff: 0
max-step-num: 2500000000
actor-activation-fn: ['relu', 'relu', 'None']
replay-buffer-size: 1000000
loss-output-smooth-coeff: 0.5
state-dim: 20
expert-index: None
tau: 0.001
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
total-step-num: 2500000000
epoch-num: 500
interpolation: False
actor-weight-decay: 1e-06
critic-layer-size: [256, 256]
gating-layer-size: [32, 32]
action-dim: 12
max-episode-num: 5000000
loss-entropy-coeff: 0.0
gating-index: None
filter-torque: False
expert-num: 4
epoch-step-num: 5000000
joint-interpolation: True
dsr-gait-period: 0.6
bullet-default-PD: False
task-weight: 0.5
record-start-size: 10000.0
imitation-weight: 0.5
max-test-time: 10
max-path-step: 5000
replay-start-size: 10000
env-id: HumanoidBalanceFilter-v0
filter-action: True
HLC-frequency: 25
n-step: 1
gamma: 0.955
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
batch-size: 128
actor-l2-reg: 0.0003
LLC-frequency: 500
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
test-num: 4
gating-activation-fn: ['relu', 'relu', 'None']
actor-lr: 0.0003
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
reward-scale: 0.1
train-step-num: 1
critic-weight-decay: 1e-06
critic-l2-reg: 0.0003
squash-action: True
critic-activation-fn: ['relu', 'relu', 'None']
loss-output-bound-coeff: 0.0
dsr-gait-freq: 1.667
categorical-distribution: {'v_max': 250, 'v_min': -10, 'n_atoms': 51}
replay-ratio: 1
action-bounds: [[-0.5236 -2.666  -0.1    -0.5236 -2.666  -0.1    -0.5236 -2.666  -0.1
  -0.5236 -2.666  -0.1   ]
 [ 0.5236  1.548   2.09    0.5236  1.548   2.09    0.5236  1.548   2.09
   0.5236  1.548   2.09  ]]
actor-layer-size: [256, 256]
critic-lr: 0.0003
max-train-time: 10
rollout-step-num: 1
