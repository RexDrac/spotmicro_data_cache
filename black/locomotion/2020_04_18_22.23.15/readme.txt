critic-weight-decay: 1e-06
state-dim: 20
expert-num: 4
n-step: 1
rollout-step-num: 1
critic-layer-size: [256, 256]
squash-action: True
task-weight: 0.5
max-train-time: 10
Physics-frequency: 1000
prioritized-exp-replay: True
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
loss-output-diff-coeff: 0
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
loss-output-smooth-coeff: 0.5
epoch-step-num: 5000000
imitation-weight: 0.5
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
expert-index: None
categorical-distribution: {'v_min': -10, 'v_max': 250, 'n_atoms': 51}
max-episode-num: 5000000
actor-weight-decay: 1e-06
dsr-gait-period: 0.6
gating-activation-fn: ['relu', 'relu', 'None']
max-step-num: 2500000000
LLC-frequency: 500
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
tau: 0.001
gamma: 0.955
epoch-num: 500
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
record-start-size: 10000.0
loss-output-bound-coeff: 0.0
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
actor-layer-size: [256, 256]
max-test-time: 10
replay-buffer-size: 1000000
gating-index: None
reward-scale: 0.1
action-dim: 12
actor-lr: 0.0003
critic-lr: 0.0003
batch-size: 128
max-path-step: 5000
HLC-frequency: 25
filter-torque: False
action-bounds: [[-0.5236 -2.666  -0.1    -0.5236 -2.666  -0.1    -0.5236 -2.666  -0.1
  -0.5236 -2.666  -0.1   ]
 [ 0.5236  1.548   2.09    0.5236  1.548   2.09    0.5236  1.548   2.09
   0.5236  1.548   2.09  ]]
replay-ratio: 1
train-step-num: 1
critic-l2-reg: 0.0003
loss-entropy-coeff: 0.0
env-id: HumanoidBalanceFilter-v0
max-path-num: 20
actor-l2-reg: 0.0003
gating-layer-size: [32, 32]
dsr-gait-freq: 1.667
test-num: 4
total-step-num: 2500000000
joint-interpolation: True
replay-start-size: 10000
filter-action: True
critic-activation-fn: ['relu', 'relu', 'None']
actor-activation-fn: ['relu', 'relu', 'None']
render-eval: False
interpolation: False
bullet-default-PD: False
