# Map User Identification With Eye Movement
The two zipped csv files contain the LOC (self-localization) and ORI (spatial orientation) experiment gaze data, respectively. The data were exported by Tobii Studio.   
The csv file consists of the following fields:  
'ParticipantID': anonymized participant id  
'TaskID': LOC01 - LOC20, ORI01 - ORI20, 20 tasks (trials) in each experiment  
'TaskType': 'SelfLocation' or 'Orientation'  
'RecordingTimestamp': timestamp of the gaze sample recorded by Tobii (milliseconds)  
'FixationIndex': fixation index  
'SaccadeIndex': saccade index  
'GazeEventType': 'Fixation', 'Saccade' or 'Unclassified', classified by Tobii  
'GazeEventDuration': duration of the gaze event (milliseconds)  
'FixationPointX (MCSpx)': screen X corrdinate of the fixation (screen pixel)  
'FixationPointY (MCSpx)', screen Y corrdinate of the fixation (screen pixel)  
'SaccadicAmplitude': the amplitude of the saccade  
'GazePointIndex': gaze point index  
'GazePointX (MCSpx)': screen X corrdinate of the gaze point (screen pixel)  
'GazePointY (MCSpx)': screen Y corrdinate of the gaze point (screen pixel)  
'PupilLeft': left pupil size (millimeter)  
'PupilRight': right pupil size (millimeter)  
