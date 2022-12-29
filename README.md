# ModelTuner2
Keras based Hyper parameters tunning: 

  tuner = keras_tuner.RandomSearch(
      hypermodel=build_model,
      objective="val_accuracy",
      max_trials=3,
      executions_per_trial=2,
      overwrite=True,
      directory="my_dir",
      project_name="helloworld",
  )
