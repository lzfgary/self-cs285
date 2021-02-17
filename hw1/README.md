###ep_len: 200, batch_size: 5000

####Ant:
Eval_AverageReturn : 185.4827880859375\
Eval_StdReturn : 2.181859016418457\
Train_AverageReturn : 186.57180786132812\
Train_StdReturn : 1.0398606061935425\
Training Loss : 3.0400636868987974e-11\
Initial_DataCollection_AverageReturn : 186.57180786132812

####HalfCheetah:
Eval_AverageReturn : 185.09890747070312\
Eval_StdReturn : 2.213763475418091\
Train_AverageReturn : 186.57180786132812\
Train_StdReturn : 1.0398606061935425\
Training Loss : 4.861962499269623e-10\
Initial_DataCollection_AverageReturn : 186.57180786132812

###ep_len: 200 - 1000

Eval_AverageReturn : 184.34957885742188\
Eval_StdReturn : 2.6698198318481445\
Train_AverageReturn : 186.57180786132812\
Train_StdReturn : 1.0398606061935425\
Training Loss : 4.861962499269623e-10\
Initial_DataCollection_AverageReturn : 186.57180786132812

Eval_AverageReturn : 280.0325622558594\
Eval_StdReturn : 1.8313210010528564\
Train_AverageReturn : 282.02777099609375\
Train_StdReturn : 1.0013349056243896\
Training Loss : 1.7254391195820062e-06\
Initial_DataCollection_AverageReturn : 282.02777099609375

Eval_AverageReturn : 378.0556335449219\
Eval_StdReturn : 1.043840765953064\
Train_AverageReturn : 377.22119140625\
Train_StdReturn : 0.4982987940311432\
Training Loss : 7.274270630297508e-10
Initial_DataCollection_AverageReturn : 377.22119140625

Eval_AverageReturn : 474.2705383300781\
Eval_StdReturn : 1.851593017578125\
Train_AverageReturn : 472.5151062011719\
Train_StdReturn : 0.054718017578125\
Training Loss : 3.261701806422934e-07\
Initial_DataCollection_AverageReturn : 472.5151062011719

Eval_AverageReturn : 568.5481567382812\
Eval_StdReturn : 1.923583984375\
Train_AverageReturn : 568.1331787109375\
Train_StdReturn : 0.0933532789349556\
Training Loss : 6.42613606771647e-09\
Initial_DataCollection_AverageReturn : 568.1331787109375

Eval_AverageReturn : 758.0548706054688\
Eval_StdReturn : 0.11871337890625\
Train_AverageReturn : 759.3837890625\
Train_StdReturn : 0.374908447265625\
Training Loss : 3.2036772540378067e-11\
Initial_DataCollection_AverageReturn : 759.3837890625

Eval_AverageReturn : 853.748291015625\
Eval_StdReturn : 0.582977294921875\
Train_AverageReturn : 855.0111083984375\
Train_StdReturn : 0.513671875\
Training Loss : 1.8447814456590272e-11\
Initial_DataCollection_AverageReturn : 855.0111083984375

Eval_AverageReturn : 954.3577880859375\
Eval_StdReturn : 0.0\
Train_AverageReturn : 951.290771484375\
Train_StdReturn : 0.0\
Training Loss : 1.0281345206079005e-15\
Initial_DataCollection_AverageReturn : 951.290771484375

##Part 2:
###running on ant with  `python cs285/scripts/run_hw1.py --expert_policy_file cs285/policies/experts/Ant.pkl --env_name Ant-v2 --exp_name test_bc_ant --n_iter 15 --do_dagger --expert_data cs285/expert_data/expert_data_Ant-v2.pkl --num_agent_train_steps_per_iter 1000 --batch_size 5000 --video_log_freq -1`
#### Note: Abnormal behavior.
#### Current guess: the change in loss might be caused by missing local minimum during gradient descent.

********** Iteration 0 ************

Collecting data to be used for training...

Training agent using sampled data from replay buffer...

Beginning logging procedure...

Collecting data for eval...
Eval_AverageReturn : 953.139892578125
Eval_StdReturn : 0.0
Eval_MaxReturn : 953.139892578125
Eval_MinReturn : 953.139892578125
Eval_AverageEpLen : 1000.0
Train_AverageReturn : 952.2467041015625
Train_StdReturn : 1.4726136922836304
Train_MaxReturn : 953.9280395507812
Train_MinReturn : 949.9859619140625
Train_AverageEpLen : 1000.0
Train_EnvstepsSoFar : 5000
TimeSinceStart : 5.77745795249939
Training Loss : 2.8230695453985164e-15
Initial_DataCollection_AverageReturn : 952.2467041015625
Done logging...




********** Iteration 1 ************

Collecting data to be used for training...

Relabelling collected observations with labels from an expert policy...

Training agent using sampled data from replay buffer...

Beginning logging procedure...

Collecting data for eval...
Eval_AverageReturn : 576.54052734375
Eval_StdReturn : 0.0
Eval_MaxReturn : 576.54052734375
Eval_MinReturn : 576.54052734375
Eval_AverageEpLen : 1000.0
Train_AverageReturn : 952.6520385742188
Train_StdReturn : 2.2967355251312256
Train_MaxReturn : 956.520263671875
Train_MinReturn : 949.3157958984375
Train_AverageEpLen : 1000.0
Train_EnvstepsSoFar : 10000
TimeSinceStart : 13.992203950881958
Training Loss : 4.863557304015786e-16
Initial_DataCollection_AverageReturn : 952.2467041015625
Done logging...




********** Iteration 2 ************

Collecting data to be used for training...

Relabelling collected observations with labels from an expert policy...

Training agent using sampled data from replay buffer...

Beginning logging procedure...

Collecting data for eval...
Eval_AverageReturn : 654.9019775390625
Eval_StdReturn : 0.0
Eval_MaxReturn : 654.9019775390625
Eval_MinReturn : 654.9019775390625
Eval_AverageEpLen : 1000.0
Train_AverageReturn : 576.7042236328125
Train_StdReturn : 1.2866122722625732
Train_MaxReturn : 577.8253173828125
Train_MinReturn : 574.3837890625
Train_AverageEpLen : 1000.0
Train_EnvstepsSoFar : 15000
TimeSinceStart : 23.941823959350586
Training Loss : 1.8262930315309173e-15
Initial_DataCollection_AverageReturn : 952.2467041015625
Done logging...




********** Iteration 3 ************

Collecting data to be used for training...

Relabelling collected observations with labels from an expert policy...

Training agent using sampled data from replay buffer...

Beginning logging procedure...

Collecting data for eval...
Eval_AverageReturn : 508.632080078125
Eval_StdReturn : 0.0
Eval_MaxReturn : 508.632080078125
Eval_MinReturn : 508.632080078125
Eval_AverageEpLen : 1000.0
Train_AverageReturn : 637.1800537109375
Train_StdReturn : 10.451118469238281
Train_MaxReturn : 656.29345703125
Train_MinReturn : 627.0935668945312
Train_AverageEpLen : 1000.0
Train_EnvstepsSoFar : 20000
TimeSinceStart : 35.95705008506775
Training Loss : 1.4606371800073614e-17
Initial_DataCollection_AverageReturn : 952.2467041015625
Done logging...




********** Iteration 4 ************

Collecting data to be used for training...

Relabelling collected observations with labels from an expert policy...

Training agent using sampled data from replay buffer...

Beginning logging procedure...

Collecting data for eval...
Eval_AverageReturn : 382.49041748046875
Eval_StdReturn : 0.0
Eval_MaxReturn : 382.49041748046875
Eval_MinReturn : 382.49041748046875
Eval_AverageEpLen : 1000.0
Train_AverageReturn : 450.58990478515625
Train_StdReturn : 33.05551528930664
Train_MaxReturn : 491.98345947265625
Train_MinReturn : 409.5834045410156
Train_AverageEpLen : 1000.0
Train_EnvstepsSoFar : 25000
TimeSinceStart : 49.925292015075684
Training Loss : 3.944969554476284e-15
Initial_DataCollection_AverageReturn : 952.2467041015625
Done logging...




********** Iteration 5 ************

Collecting data to be used for training...

Relabelling collected observations with labels from an expert policy...

Training agent using sampled data from replay buffer...

Beginning logging procedure...

Collecting data for eval...
Eval_AverageReturn : 430.53924560546875
Eval_StdReturn : 0.0
Eval_MaxReturn : 430.53924560546875
Eval_MinReturn : 430.53924560546875
Eval_AverageEpLen : 1000.0
Train_AverageReturn : 401.87371826171875
Train_StdReturn : 10.400741577148438
Train_MaxReturn : 420.3683166503906
Train_MinReturn : 388.7742919921875
Train_AverageEpLen : 1000.0
Train_EnvstepsSoFar : 30000
TimeSinceStart : 65.89760899543762
Training Loss : 2.8521630095543335e-15
Initial_DataCollection_AverageReturn : 952.2467041015625
Done logging...




********** Iteration 6 ************

Collecting data to be used for training...

Relabelling collected observations with labels from an expert policy...

Training agent using sampled data from replay buffer...

Beginning logging procedure...

Collecting data for eval...
Eval_AverageReturn : 811.998779296875
Eval_StdReturn : 0.0
Eval_MaxReturn : 811.998779296875
Eval_MinReturn : 811.998779296875
Eval_AverageEpLen : 1000.0
Train_AverageReturn : 434.2442321777344
Train_StdReturn : 5.857932090759277
Train_MaxReturn : 440.7859191894531
Train_MinReturn : 425.40594482421875
Train_AverageEpLen : 1000.0
Train_EnvstepsSoFar : 35000
TimeSinceStart : 83.30281686782837
Training Loss : 1.1010102696218382e-07
Initial_DataCollection_AverageReturn : 952.2467041015625
Done logging...




********** Iteration 7 ************

Collecting data to be used for training...

Relabelling collected observations with labels from an expert policy...

Training agent using sampled data from replay buffer...

Beginning logging procedure...

Collecting data for eval...
Eval_AverageReturn : -462.16552734375
Eval_StdReturn : 0.0
Eval_MaxReturn : -462.16552734375
Eval_MinReturn : -462.16552734375
Eval_AverageEpLen : 1000.0
Train_AverageReturn : 779.8566284179688
Train_StdReturn : 20.72500991821289
Train_MaxReturn : 813.455810546875
Train_MinReturn : 754.8848876953125
Train_AverageEpLen : 1000.0
Train_EnvstepsSoFar : 40000
TimeSinceStart : 103.16213393211365
Training Loss : 7.157774373212078e-12
Initial_DataCollection_AverageReturn : 952.2467041015625
Done logging...




********** Iteration 8 ************

Collecting data to be used for training...

Relabelling collected observations with labels from an expert policy...

Training agent using sampled data from replay buffer...

Beginning logging procedure...

Collecting data for eval...
Eval_AverageReturn : 751.4326171875
Eval_StdReturn : 0.0
Eval_MaxReturn : 751.4326171875
Eval_MinReturn : 751.4326171875
Eval_AverageEpLen : 1000.0
Train_AverageReturn : -427.49261474609375
Train_StdReturn : 8.343066215515137
Train_MaxReturn : -419.76153564453125
Train_MinReturn : -442.09051513671875
Train_AverageEpLen : 1000.0
Train_EnvstepsSoFar : 45000
TimeSinceStart : 125.76586174964905
Training Loss : 1.1983285330623519e-15
Initial_DataCollection_AverageReturn : 952.2467041015625
Done logging...




********** Iteration 9 ************

Collecting data to be used for training...

Relabelling collected observations with labels from an expert policy...

Training agent using sampled data from replay buffer...

Beginning logging procedure...

Collecting data for eval...
Eval_AverageReturn : 734.3667602539062
Eval_StdReturn : 0.0
Eval_MaxReturn : 734.3667602539062
Eval_MinReturn : 734.3667602539062
Eval_AverageEpLen : 1000.0
Train_AverageReturn : 659.140625
Train_StdReturn : 100.71415710449219
Train_MaxReturn : 765.9169921875
Train_MinReturn : 500.4462890625
Train_AverageEpLen : 1000.0
Train_EnvstepsSoFar : 50000
TimeSinceStart : 150.13899207115173
Training Loss : 1.8494581120889015e-15
Initial_DataCollection_AverageReturn : 952.2467041015625
Done logging...




********** Iteration 10 ************

Collecting data to be used for training...

Relabelling collected observations with labels from an expert policy...

Training agent using sampled data from replay buffer...

Beginning logging procedure...

Collecting data for eval...
Eval_AverageReturn : -713.9569702148438
Eval_StdReturn : 0.0
Eval_MaxReturn : -713.9569702148438
Eval_MinReturn : -713.9569702148438
Eval_AverageEpLen : 1000.0
Train_AverageReturn : 617.9364624023438
Train_StdReturn : 269.0841064453125
Train_MaxReturn : 748.28466796875
Train_MinReturn : 16.333480834960938
Train_AverageEpLen : 840.0
Train_EnvstepsSoFar : 55040
TimeSinceStart : 175.44331908226013
Training Loss : 2.234688061225447e-15
Initial_DataCollection_AverageReturn : 952.2467041015625
Done logging...




********** Iteration 11 ************

Collecting data to be used for training...

Relabelling collected observations with labels from an expert policy...

Training agent using sampled data from replay buffer...

Beginning logging procedure...

Collecting data for eval...
Eval_AverageReturn : 482.645263671875
Eval_StdReturn : 0.0
Eval_MaxReturn : 482.645263671875
Eval_MinReturn : 482.645263671875
Eval_AverageEpLen : 1000.0
Train_AverageReturn : -54.25443649291992
Train_StdReturn : 243.2025146484375
Train_MaxReturn : 709.75
Train_MinReturn : -655.574462890625
Train_AverageEpLen : 181.90625
Train_EnvstepsSoFar : 60861
TimeSinceStart : 203.34855389595032
Training Loss : 2.948158362414688e-05
Initial_DataCollection_AverageReturn : 952.2467041015625
Done logging...




********** Iteration 12 ************

Collecting data to be used for training...

Relabelling collected observations with labels from an expert policy...

Training agent using sampled data from replay buffer...

Beginning logging procedure...

Collecting data for eval...
Eval_AverageReturn : 493.6513671875
Eval_StdReturn : 0.0
Eval_MaxReturn : 493.6513671875
Eval_MinReturn : 493.6513671875
Eval_AverageEpLen : 1000.0
Train_AverageReturn : 495.3199768066406
Train_StdReturn : 5.977340221405029
Train_MaxReturn : 503.8058776855469
Train_MinReturn : 485.33990478515625
Train_AverageEpLen : 1000.0
Train_EnvstepsSoFar : 65861
TimeSinceStart : 232.73425793647766
Training Loss : 2.7779337870015297e-06
Initial_DataCollection_AverageReturn : 952.2467041015625
Done logging...




********** Iteration 13 ************

Collecting data to be used for training...

Relabelling collected observations with labels from an expert policy...

Training agent using sampled data from replay buffer...

Beginning logging procedure...

Collecting data for eval...
Eval_AverageReturn : -51.137725830078125
Eval_StdReturn : 173.03953552246094
Eval_MaxReturn : 10.317827224731445
Eval_MinReturn : -871.000732421875
Eval_AverageEpLen : 78.41666666666667
Train_AverageReturn : 503.0121154785156
Train_StdReturn : 7.991919994354248
Train_MaxReturn : 515.0599975585938
Train_MinReturn : 493.36126708984375
Train_AverageEpLen : 1000.0
Train_EnvstepsSoFar : 70861
TimeSinceStart : 265.4773669242859
Training Loss : 2.3569853055960266e-06
Initial_DataCollection_AverageReturn : 952.2467041015625
Done logging...




********** Iteration 14 ************

Collecting data to be used for training...

Relabelling collected observations with labels from an expert policy...

Training agent using sampled data from replay buffer...

Beginning logging procedure...

Collecting data for eval...
Eval_AverageReturn : 150.26626586914062
Eval_StdReturn : 0.0
Eval_MaxReturn : 150.26626586914062
Eval_MinReturn : 150.26626586914062
Eval_AverageEpLen : 1000.0
Train_AverageReturn : -58.1474609375
Train_StdReturn : 179.57131958007812
Train_MaxReturn : 9.6533842086792
Train_MinReturn : -899.551513671875
Train_AverageEpLen : 82.70588235294117
Train_EnvstepsSoFar : 76485
TimeSinceStart : 300.6505448818207
Training Loss : 2.031440453720279e-05
Initial_DataCollection_AverageReturn : 952.2467041015625
Done logging...