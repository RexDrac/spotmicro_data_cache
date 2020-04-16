dsr-gait-freq: 1.667
critic-weight-decay: 1e-06
Physics-frequency: 1000
loss-entropy-coeff: 0.0
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
env-id: HumanoidBalanceFilter-v0
replay-start-size: 10000
expert-num: 4
filter-torque: False
n-step: 1
filter-action: True
loss-output-bound-coeff: 0.0
max-path-num: 20
epoch-step-num: 5000000
action-dim: 12
max-episode-num: 5000000
tau: 0.001
joint-interpolation: True
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
record-start-size: 10000.0
gating-index: None
reward-scale: 0.1
total-step-num: 2500000000
dsr-gait-period: 0.6
squash-action: True
expert-index: None
max-step-num: 2500000000
max-train-time: 10
actor-activation-fn: ['relu', 'relu', 'None']
task-weight: 0.5
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
state-dim: 20
loss-output-smooth-coeff: 0.1
batch-size: 128
epoch-num: 500
actor-l2-reg: 0.0003
critic-activation-fn: ['relu', 'relu', 'None']
test-num: 4
critic-lr: 0.0003
loss-output-diff-coeff: 0
actor-layer-size: [256, 256]
gating-activation-fn: ['relu', 'relu', 'None']
train-step-num: 1
action-bounds: [[-0.5236 -2.666  -0.1    -0.5236 -2.666  -0.1    -0.5236 -2.666  -0.1
  -0.5236 -2.666  -0.1   ]
 [ 0.5236  1.548   2.09    0.5236  1.548   2.09    0.5236  1.548   2.09
   0.5236  1.548   2.09  ]]
gamma: 0.955
bullet-default-PD: False
imitation-weight: 0.5
categorical-distribution: {'v_max': 250, 'v_min': -10, 'n_atoms': 51}
critic-l2-reg: 0.0003
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
interpolation: False
gating-layer-size: [32, 32]
actor-weight-decay: 1e-06
rollout-step-num: 1
prioritized-exp-replay: True
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
max-path-step: 5000
replay-ratio: 1
replay-buffer-size: 1000000
max-test-time: 10
render-eval: False
actor-lr: 0.0003
HLC-frequency: 25
critic-layer-size: [256, 256]
LLC-frequency: 500
