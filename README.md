Problem Statement:
Given a set of segments with associated factors and a set of respondents providing binary (0 or 1) answers for those segments, the goal was to calculate a score for each respondent by multiplying the segment answers with the respective segment factors. Based on the highest score, the corresponding segment for each respondent was identified.

Steps Involved:
Segment and Factor Data: The segment data consists of multiple segments, each with its own set of associated factors. The factors represent the weight or importance assigned to each segment.

Respondent Data: The respondents answered "Yes" (1) or "No" (0) for each segment, indicating their preference or selection for the segment.

Score Calculation: For each respondent, the score was calculated as a sum-product of the respondent’s answers (0 or 1) and the factors of the respective segments.

Determine Highest Scoring Segment: The segment with the highest calculated score was identified for each respondent.

Result: Output a final DataFrame with respondents and their corresponding highest scoring segment.

Conclusion:
Worked with multi-dimensional data (segments, factors, respondents).
Used pandas for data manipulation, and calculations.
Implemented a practical business calculation based on input data.
