# This is the README for the paper "Is It the Revision or the Word? 
# Separating Revision Signals from Marker Words in Reasoning Traces"

The order in whcih to run the code is relatively self-explanatory. The maximum requirements for
running this code are an A100 GPU and a google colab pro subscription. 

Here is the order in which to run each file

## Task 1: Data Pipeline
This gives the reasoning traces required for all analysis
## Label_Thing_Planning_Study
This is where the revision markers are extracted from the responses and labelled by gpt-4o
## Activation_extractor
This is where activations are extracted from the revisions for the probe and the necessity tests
## Paper_2_0_Task6_Filler_Recovery
This is where filler words are labelled by gpt-4o
## Paper2_1_Filler_Activation_Extraction
This is where we extract the activations from the filler words for teh probe and the necessity tests.
## Paper2_2_Construct_Validity_Probe
We run this code to create, train, and evaluate the probe
## Paper2_3_Lexical_Filler_Control
We run this code for the lexical suppression. 
## Paper2_4_Steering_Powered_Run.ipynb
We run this code to steer the models responses for the steering necessity test
## Paper2_5_Parser_and_GroundTruth_Repair
## Paper2_6_Verification_and_Audits
## Paper2_7_Divergence_Control (1)
## Paper2_8_GPT4o_Validation (1)
## Paper2_9_Repetition and Controls
