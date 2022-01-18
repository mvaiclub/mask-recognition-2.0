# mask-recognition-2.0
Our mask recognition project, back from last year! :)

## How to run the project
So far, the training stage been completed.
That means that if you run the command "python3 train_mask_detector.py -d dataset", 
one will be able to see the model training for themselves. 

Update 1/17/2022: 
Video and single image detection have also been completed.
In order to run video detection, please run 'python3 detect_mask_video.py'

More specifically, one can expect 
- A graph (plot.png) on training loss / accuracy
- A saved mask detector model (mask_detector.model)
- An accuracy report, printed to console

NOTE: There are some external libraries you may need to install with the virtualenv
To install them, run the command "pip3 install -r requirements.txt" (after you activate the virtualenv)

