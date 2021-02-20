python cs285/scripts/run_hw1.py --expert_policy_file cs285/policies/experts/Ant.pkl --env_name Ant-v2 --exp_name test_bc_ant --n_iter 1 --expert_data cs285/expert_data/expert_data_Ant-v2.pkl --batch_size=100 --train_batch_size=2000 --eval_batch_size=50000 --n_layers=2 --size=64 --video_log_freq=-1

Collecting data for eval...
Eval_AverageReturn : 4449.857421875
Eval_StdReturn : 942.77880859375
Eval_MaxReturn : 4867.703125
Eval_MinReturn : 767.1270751953125
Eval_AverageEpLen : 975.3653846153846
Train_AverageReturn : 4713.6533203125
Train_StdReturn : 12.196533203125
Train_MaxReturn : 4725.849609375
Train_MinReturn : 4701.45654296875
Train_AverageEpLen : 1000.0
Train_EnvstepsSoFar : 0
TimeSinceStart : 32.44271898269653
Training Loss : 0.0005393518367782235
Initial_DataCollection_AverageReturn : 4713.6533203125
Done logging...


python cs285/scripts/run_hw1.py --expert_policy_file cs285/policies/experts/HalfCheetah.pkl --env_name HalfCheetah-v2 --exp_name test_bc_hcheetah --n_iter 1 --expert_data cs285/expert_data/expert_data_HalfCheetah-v2.pkl --batch_size=1000 --eval_batch_size=50000 --n_layers=2 --size=64 --video_log_freq=-1

Collecting data for eval...
Eval_AverageReturn : 4028.881591796875
Eval_StdReturn : 95.12850189208984
Eval_MaxReturn : 4254.23388671875
Eval_MinReturn : 3794.83740234375
Eval_AverageEpLen : 1000.0
Train_AverageReturn : 4205.7783203125
Train_StdReturn : 83.038818359375
Train_MaxReturn : 4288.81689453125
Train_MinReturn : 4122.7392578125
Train_AverageEpLen : 1000.0
Train_EnvstepsSoFar : 0
TimeSinceStart : 15.236982107162476
Training Loss : 0.0013567192945629358
Initial_DataCollection_AverageReturn : 4205.7783203125
Done logging...

python cs285/scripts/run_hw1.py --expert_policy_file cs285/policies/experts/Ant.pkl --env_name Ant-v2 --exp_name dagger_ant --n_iter 10 --do_dagger --expert_data cs285/expert_data/expert_data_Ant-v2.pkl --batch_size=100 --train_batch_size=2000 --eval_batch_size=50000 --n_layers=2 --size=64 --video_log_freq=-1
--video_log_freq -1

********** Iteration 0 ************

Training agent using sampled data from replay buffer...

Beginning logging procedure...

Collecting data for eval...
Eval_AverageReturn : 4449.857421875
Eval_StdReturn : 942.77880859375
Eval_MaxReturn : 4867.703125
Eval_MinReturn : 767.1270751953125
Eval_AverageEpLen : 975.3653846153846
Train_AverageReturn : 4713.6533203125
Train_StdReturn : 12.196533203125
Train_MaxReturn : 4725.849609375
Train_MinReturn : 4701.45654296875
Train_AverageEpLen : 1000.0
Train_EnvstepsSoFar : 0
TimeSinceStart : 31.61956000328064
Training Loss : 0.0005393518367782235
Initial_DataCollection_AverageReturn : 4713.6533203125
Done logging...




********** Iteration 1 ************

Collecting data to be used for training...

Relabelling collected observations with labels from an expert policy...

Training agent using sampled data from replay buffer...

Beginning logging procedure...

Collecting data for eval...
Eval_AverageReturn : 4660.82470703125
Eval_StdReturn : 382.8813781738281
Eval_MaxReturn : 4906.265625
Eval_MinReturn : 2080.77197265625
Eval_AverageEpLen : 1000.0
Train_AverageReturn : 4586.3154296875
Train_StdReturn : 0.0
Train_MaxReturn : 4586.3154296875
Train_MinReturn : 4586.3154296875
Train_AverageEpLen : 1000.0
Train_EnvstepsSoFar : 1000
TimeSinceStart : 63.491549015045166
Training Loss : 0.00024702216614969075
Initial_DataCollection_AverageReturn : 4713.6533203125
Done logging...




********** Iteration 2 ************

Collecting data to be used for training...

Relabelling collected observations with labels from an expert policy...

Training agent using sampled data from replay buffer...

Beginning logging procedure...

Collecting data for eval...
Eval_AverageReturn : 4656.1376953125
Eval_StdReturn : 398.0134582519531
Eval_MaxReturn : 5002.4853515625
Eval_MinReturn : 2137.415771484375
Eval_AverageEpLen : 996.6470588235294
Train_AverageReturn : 4774.279296875
Train_StdReturn : 0.0
Train_MaxReturn : 4774.279296875
Train_MinReturn : 4774.279296875
Train_AverageEpLen : 1000.0
Train_EnvstepsSoFar : 2000
TimeSinceStart : 97.01167488098145
Training Loss : 0.00017237676365766674
Initial_DataCollection_AverageReturn : 4713.6533203125
Done logging...




********** Iteration 3 ************

Collecting data to be used for training...

Relabelling collected observations with labels from an expert policy...

Training agent using sampled data from replay buffer...

Beginning logging procedure...

Collecting data for eval...
Eval_AverageReturn : 4571.58251953125
Eval_StdReturn : 843.9422607421875
Eval_MaxReturn : 4910.79296875
Eval_MinReturn : 255.72274780273438
Eval_AverageEpLen : 981.7843137254902
Train_AverageReturn : 4746.14892578125
Train_StdReturn : 0.0
Train_MaxReturn : 4746.14892578125
Train_MinReturn : 4746.14892578125
Train_AverageEpLen : 1000.0
Train_EnvstepsSoFar : 3000
TimeSinceStart : 131.34667015075684
Training Loss : 0.00010770710650831461
Initial_DataCollection_AverageReturn : 4713.6533203125
Done logging...




********** Iteration 4 ************

Collecting data to be used for training...

Relabelling collected observations with labels from an expert policy...

Training agent using sampled data from replay buffer...

Beginning logging procedure...

Collecting data for eval...
Eval_AverageReturn : 4635.38427734375
Eval_StdReturn : 579.1985473632812
Eval_MaxReturn : 4921.49072265625
Eval_MinReturn : 602.2177734375
Eval_AverageEpLen : 983.1764705882352
Train_AverageReturn : 4710.0888671875
Train_StdReturn : 0.0
Train_MaxReturn : 4710.0888671875
Train_MinReturn : 4710.0888671875
Train_AverageEpLen : 1000.0
Train_EnvstepsSoFar : 4000
TimeSinceStart : 163.53642010688782
Training Loss : 0.00010818470764206722
Initial_DataCollection_AverageReturn : 4713.6533203125
Done logging...




********** Iteration 5 ************

Collecting data to be used for training...

Relabelling collected observations with labels from an expert policy...

Training agent using sampled data from replay buffer...

Beginning logging procedure...

Collecting data for eval...
Eval_AverageReturn : 4565.9716796875
Eval_StdReturn : 722.2318725585938
Eval_MaxReturn : 5030.4501953125
Eval_MinReturn : 412.74066162109375
Eval_AverageEpLen : 985.2352941176471
Train_AverageReturn : 4813.49267578125
Train_StdReturn : 0.0
Train_MaxReturn : 4813.49267578125
Train_MinReturn : 4813.49267578125
Train_AverageEpLen : 1000.0
Train_EnvstepsSoFar : 5000
TimeSinceStart : 196.74793028831482
Training Loss : 9.687383135315031e-05
Initial_DataCollection_AverageReturn : 4713.6533203125
Done logging...




********** Iteration 6 ************

Collecting data to be used for training...

Relabelling collected observations with labels from an expert policy...

Training agent using sampled data from replay buffer...

Beginning logging procedure...

Collecting data for eval...
Eval_AverageReturn : 4656.77587890625
Eval_StdReturn : 528.7806396484375
Eval_MaxReturn : 4941.01220703125
Eval_MinReturn : 1012.6410522460938
Eval_AverageEpLen : 1000.0
Train_AverageReturn : 4634.640625
Train_StdReturn : 0.0
Train_MaxReturn : 4634.640625
Train_MinReturn : 4634.640625
Train_AverageEpLen : 1000.0
Train_EnvstepsSoFar : 6000
TimeSinceStart : 231.11140894889832
Training Loss : 0.00011190496297786012
Initial_DataCollection_AverageReturn : 4713.6533203125
Done logging...




********** Iteration 7 ************

Collecting data to be used for training...

Relabelling collected observations with labels from an expert policy...

Training agent using sampled data from replay buffer...

Beginning logging procedure...

Collecting data for eval...
Eval_AverageReturn : 4719.97509765625
Eval_StdReturn : 87.00487518310547
Eval_MaxReturn : 4915.6865234375
Eval_MinReturn : 4543.6640625
Eval_AverageEpLen : 1000.0
Train_AverageReturn : 4810.53955078125
Train_StdReturn : 0.0
Train_MaxReturn : 4810.53955078125
Train_MinReturn : 4810.53955078125
Train_AverageEpLen : 1000.0
Train_EnvstepsSoFar : 7000
TimeSinceStart : 268.17283511161804
Training Loss : 0.00016922291251830757
Initial_DataCollection_AverageReturn : 4713.6533203125
Done logging...




********** Iteration 8 ************

Collecting data to be used for training...

Relabelling collected observations with labels from an expert policy...

Training agent using sampled data from replay buffer...

Beginning logging procedure...

Collecting data for eval...
Eval_AverageReturn : 4756.978515625
Eval_StdReturn : 82.29960632324219
Eval_MaxReturn : 4922.7197265625
Eval_MinReturn : 4546.9814453125
Eval_AverageEpLen : 1000.0
Train_AverageReturn : 4793.68310546875
Train_StdReturn : 0.0
Train_MaxReturn : 4793.68310546875
Train_MinReturn : 4793.68310546875
Train_AverageEpLen : 1000.0
Train_EnvstepsSoFar : 8000
TimeSinceStart : 302.2322211265564
Training Loss : 0.0001332226675003767
Initial_DataCollection_AverageReturn : 4713.6533203125
Done logging...




********** Iteration 9 ************

Collecting data to be used for training...

Relabelling collected observations with labels from an expert policy...

Training agent using sampled data from replay buffer...

Beginning logging procedure...

Collecting data for eval...
Eval_AverageReturn : 4747.02783203125
Eval_StdReturn : 110.0713882446289
Eval_MaxReturn : 4957.7626953125
Eval_MinReturn : 4246.73046875
Eval_AverageEpLen : 998.3333333333334
Train_AverageReturn : 4585.67529296875
Train_StdReturn : 0.0
Train_MaxReturn : 4585.67529296875
Train_MinReturn : 4585.67529296875
Train_AverageEpLen : 1000.0
Train_EnvstepsSoFar : 9000
TimeSinceStart : 337.50450706481934
Training Loss : 9.650728316046298e-05
Initial_DataCollection_AverageReturn : 4713.6533203125
Done logging...



python cs285/scripts/run_hw1.py --expert_policy_file cs285/policies/experts/HalfCheetah.pkl --env_name HalfCheetah-v2 --exp_name test_bc_hcheetah --n_iter 10 --do_dagger --expert_data cs285/expert_data/expert_data_HalfCheetah-v2.pkl --batch_size=1000 --train_batch_size=100 --eval_batch_size=50000 --n_layers=2 --size=64 --video_log_freq=-1
