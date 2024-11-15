# Free Trial Screener Experiment - README

## Goals of the Project
The primary goal of this experiment is to assess the impact of a new course enrollment flow on student behavior at Udacity. Specifically, we tested whether asking students about their available time commitment before starting the free trial could reduce the number of students who drop out of the free trial due to lack of time. By setting clearer expectations upfront, the experiment aimed to:
1. Reduce the number of frustrated students who leave the free trial.
2. Maintain or improve student retention through the free trial period and beyond.
3. Evaluate if filtering out students who cannot commit enough time helps improve conversion rates while maintaining or improving user experience.

## Conclusions
The experiment findings offer valuable insights:
- **Gross Conversion**: There was a decrease in gross conversion in the treatment group, as expected. By filtering students based on time commitment, some users chose not to proceed, which led to fewer enrollments.
- **Retention**: Retention in the treatment group increased. The filtering process helped ensure that only students who were likely to commit enough time continued in the free trial, leading to higher chances of them staying enrolled and eventually making a payment.
- **Net Conversion**: This metric showed mixed results, as it combines both gross conversion and retention. While gross conversion decreased, retention improved, leading to an unclear overall trend for net conversion.

The hypothesis that setting clearer expectations for students upfront would reduce free trial drop-off and improve retention held true for the most part. However, gross conversion decreased due to some students self-selecting out after realizing they could not commit enough time.

## Challenges
- **Multiple Metrics**: Analyzing multiple metrics (gross conversion, retention, net conversion) introduced complexity in understanding the overall impact. While the retention metric showed positive results, the decrease in gross conversion raised questions about the long-term effectiveness of the change.
- **External Factors**: The presence of large spikes in pageviews and changes in click-through rate during the experiment period (e.g., Oct 24th) could have influenced results. This required additional analysis to ensure the results were not skewed by external traffic factors.
- **Time Commitment Subjectivity**: The question regarding available time commitment (5 or more hours per week) might have been interpreted differently by students, leading to some self-selection bias. Some students who could have managed the course might have opted out prematurely due to this prompt.

## Techniques Used
- **A/B Testing**: The experiment used a controlled A/B testing design, where users were randomly assigned to either the treatment (with the new screener) or control group.
- **Sanity Checks**: We performed several sanity checks to ensure the integrity of the data, including checking the distribution of clicks, cookies, and click-through probability between the control and experiment groups.
- **Statistical Analysis**: We used z-tests to check for statistical significance of the observed changes in key metrics (gross conversion, retention, and net conversion). Practical significance was also considered, with a focus on whether observed changes met the business requirements.
- **Data Visualization**: Visual tools were used to track trends in key metrics, identify anomalies (e.g., spikes in pageviews), and ensure that the data was consistent and valid for analysis.

## Key Takeaways
- **Clearer Expectations Matter**: Setting clearer expectations about time commitment helped improve retention, but it also led to a decrease in gross conversion. This suggests that providing upfront information about course demands can help improve the student experience but may deter some potential enrollees.
- **Balancing Enrollment vs. Retention**: There is a trade-off between gross conversion and retention. While reducing enrollments may lead to higher retention among those who proceed, it could also impact overall course engagement.
- **Data Quality is Crucial**: Monitoring external factors such as traffic spikes and anomalies is critical to avoid skewed results. Regular sanity checks and careful data analysis are essential for drawing reliable conclusions from A/B tests.

## Future Work
- **Refining Time Commitment Question**: The time commitment question could be further refined to provide more flexibility or a better way to gauge student readiness without discouraging potential students.
- **Extended Experiment Duration**: A longer experiment duration would help confirm the findings and eliminate any seasonality effects that might influence the data.
- **Further Exploration of User Experience**: Qualitative data such as user surveys could help understand the reasons behind students’ decisions to opt-out or continue with the course after the free trial. This could provide deeper insights into the impact of course expectations on user behavior.
- **Experimenting with Different Course Types**: Future experiments could involve testing this change across different types of courses (e.g., beginner vs. advanced) to see if the impact varies depending on course difficulty and time commitment.
