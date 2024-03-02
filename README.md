This folder contain follwing files:

    1. Code files folder :
            1. Eng_Hinglish(Code Mixed) folder
                    1.mBART 
                        ---> 1. Training : contains code files for training mBART model.
                        ---> 2. Evaluation and Scoring : contains code files related to evaluation and postprocessing.
                        ---> 3. Results and Plots : contains Epoch_vs_Loss and Epoch_vs_Bleu plots and a jupyter notebook.
                    2.IndicBART
                        ---> Test_data predictions folder : contains test_data_predictions.txt
                        ---> epoch_wise_logs.txt : contains epoch_wise_scores of a model.
                        ---> Training.logs : contains training logs.
                        ---> run_translation.py : main code file running the model.
                        ---> train_sbatch_run.sh : contains bash script to run the IndicBART model in Ada.
                    3.mT5_small
                        ---> Test_data predictions folder : contains test_data_predictions.txt
                        ---> epoch_wise_logs.txt : contains epoch_wise_scores of a model.
                        ---> Training.logs : contains training logs.
                        ---> run_translation.py : main code file running the model.
                        ---> config.json : contains the mT5_small model architecture with hyperparameters.
                        ---> train_sbatch_run.sh : contains bash script to run the mT5_small model in Ada.
                    data
                        ---> 1. train_en_hi.json
                        ---> 2. dev_en_hi.json
                        ---> 3. test_en_hi.json

            2. English_Telugu(Code Mixed) folder
                    1.IndicBART
                        ---> Test_data predictions folder : contains test_data_predictions.txt
                        ---> Training.logs : contains training logs.
                        ---> run_translation.py : main code file running the model.
                        ---> train_sbatch_run.sh : contains bash script to run the IndicBART model in Ada.
                    2.mT5_small
                        ---> Test_data predictions folder : contains test_data_predictions.txt
                        ---> Training.logs : contains training logs.
                        ---> run_translation.py : main code file running the model.
                        ---> config.json : contains the mT5_small model architecture with hyperparameters.
                        ---> train_sbatch_run.sh : contains bash script to run the mT5_small model in Ada.
                    data
                        ---> 1. train_en_te.json
                        ---> 2. dev_en_te.json
                        ---> 3. test_en_te.json

            3. requirements.txt
                ---> It contains the list of packages required to run the IndicBART and mT5_small models. 
    
    2. Report.pdf
        ---> A document containing information about the problem statement, experiments using various models, results and output analysis.

    3. Presentation.pdf
        ---> Contains Presentation slides of the code mixed machine translation project.