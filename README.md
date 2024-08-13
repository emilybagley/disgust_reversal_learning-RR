<h2><b>Contains example analysis scripts for all planned model-agnostic analyses in the Registered Report, as well as the power analysis (included in the stage 1 Registered Report)</b></h2>

<p><b>Data checks/cleaning</b></p>
00_data_checks: will be used to make rolling exclusions. Look at data from one participant and determine if they passed the exclusion criteria.
0_data_clearning: Will be used to transform files downloaded from jatos (used to host the online experiment) to useable dataframes for use in subsequent analyses

<br>
<p></p><b>Planned analyses</b></p>
1_video_ratings_analyses: Completes models A-H as specified by the analysis plan. Full analysis of the video-rating task.
2_task_model_agnostic_analysis: Completes models 1-6. Full model-agnostic analysis of the reversal learning task
2_task_model_agnostic_analysis_nooutliers: exactly the same as above, but excludes all outliers (>1.5IQR outside of IQR)

<br>
<p></p><b>Power analysis</b></p>
<p>A_power_analysis_script: carries out both liberal and conservative power analyses, saving the outputs into power tables</p>  
B_power_analysis_plots: uses the power tables to identify the minimum required sample and plot power curves
