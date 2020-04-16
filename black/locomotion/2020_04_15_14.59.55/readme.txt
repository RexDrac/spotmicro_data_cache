action-bounds: [[-0.5236 -2.666  -0.1    -0.5236 -2.666  -0.1    -0.5236 -2.666  -0.1
  -0.5236 -2.666  -0.1   ]
 [ 0.5236  1.548   2.09    0.5236  1.548   2.09    0.5236  1.548   2.09
   0.5236  1.548   2.09  ]]
tau: 0.001
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
critic-weight-decay: 1e-06
replay-start-size: 10000
gating-index: None
filter-action: True
loss-output-diff-coeff: 0
max-train-time: 10
epoch-num: 500
max-path-step: 5000
state-dim: 20
record-start-size: 10000.0
train-step-num: 1
total-step-num: 2500000000
gamma: 0.955
replay-buffer-size: 1000000
action-dim: 12
actor-weight-decay: 1e-06
critic-lr: 0.0003
loss-output-bound-coeff: 0.0
replay-ratio: 1
gating-layer-size: [32, 32]
expert-index: None
bullet-default-PD: False
task-weight: 0.5
dsr-gait-period: 0.6
max-test-time: 10
prioritized-exp-replay: True
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
batch-size: 128
LLC-frequency: 500
dsr-gait-freq: 1.667
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
Physics-frequency: 1000
expert-num: 4
gating-activation-fn: ['relu', 'relu', 'None']
critic-l2-reg: 0.0003
categorical-distribution: {'v_max': 250, 'n_atoms': 51, 'v_min': -10}
HLC-frequency: 25
rollout-step-num: 1
max-path-num: 20
loss-entropy-coeff: 0.0
max-episode-num: 5000000
critic-activation-fn: ['relu', 'relu', 'None']
n-step: 1
actor-l2-reg: 0.0003
loss-output-smooth-coeff: 0.1
filter-torque: False
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
reward-scale: 0.1
env-id: HumanoidBalanceFilter-v0
render-eval: False
squash-action: True
joint-interpolation: True
actor-lr: 0.0003
test-num: 4
epoch-step-num: 5000000
imitation-weight: 0.5
max-step-num: 2500000000
actor-activation-fn: ['relu', 'relu', 'None']
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
critic-layer-size: [256, 256]
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
actor-layer-size: [256, 256]
interpolation: False
