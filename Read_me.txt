1) run <mlflow ui> in the terminal to activate mlflow and  "http://your-tracking-server-host:5000/"( in my case "http://127.0.0.1:5000/")
   to view experimental logs and compare different runs and experiments.The logs and artifacts will be saved in mlruns folder.
2) submitted  a screenshot of the mlflow UI along with the command used to launch the MLFlow server.
3)submitted train.ipynb file where all the command cells can be run one by one using shift+enter and the experimental logs 
  can be visualize in ml flow server and also stored in local repository mlruns 
4) Packaging of experiment as a MLflow project as conda env is also done.
   TO run the project invoke command < mlflow run . -P alpha=0.5 -P l1_ratio=0.5 > in the terminal.
   After running this command  mlflow runs your training code train .py in new conda environmnet with dependencies specified
   in conda.yaml file.
   various experiments can also be performed by changing values of alpha,l1_ratio