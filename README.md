# Analysis of Student Perfomance Factors 

## Introduction
This is a comprehensive analysis of student perfomance, gauged by the dependent variable (Exam Score) compared by the contributions of independent variables (See below variables).

<table border="1" style="border-collapse: collapse; width: 100%;">
  <thead>
    <tr>
      <th>No</th>
      <th>Feature</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>Hours_Studied</td>
      <td>Number of hours spent studying per week.</td>
    </tr>
    <tr>
      <td>2</td>
      <td>Attendance</td>
      <td>Percentage of classes attended.</td>
    </tr>
    <tr>
      <td>3</td>
      <td>Parental_Involvement</td>
      <td>Level of parental involvement in the student's education (Low, Medium, High).</td>
    </tr>
    <tr>
      <td>4</td>
      <td>Access_to_Resources</td>
      <td>Availability of educational resources (Low, Medium, High).</td>
    </tr>
    <tr>
      <td>5</td>
      <td>Extracurricular_Activities</td>
      <td>Participation in extracurricular activities (Yes, No).</td>
    </tr>
    <tr>
      <td>6</td>
      <td>Sleep_Hours</td>
      <td>Average number of hours of sleep per night.</td>
    </tr>
    <tr>
      <td>7</td>
      <td>Previous_Scores</td>
      <td>Scores from previous exams.</td>
    </tr>
    <tr>
      <td>8</td>
      <td>Motivation_Level</td>
      <td>Student's level of motivation (Low, Medium, High).</td>
    </tr>
    <tr>
      <td>9</td>
      <td>Internet_Access</td>
      <td>Availability of internet access (Yes, No).</td>
    </tr>
    <tr>
      <td>10</td>
      <td>Tutoring_Sessions</td>
      <td>Number of tutoring sessions attended per month.</td>
    </tr>
    <tr>
      <td>11</td>
      <td>Family_Income</td>
      <td>Family income level (Low, Medium, High).</td>
    </tr>
    <tr>
      <td>12</td>
      <td>Teacher_Quality</td>
      <td>Quality of the teachers (Low, Medium, High).</td>
    </tr>
    <tr>
      <td>13</td>
      <td>School_Type</td>
      <td>Type of school attended (Public, Private).</td>
    </tr>
    <tr>
      <td>14</td>
      <td>Peer_Influence</td>
      <td>Influence of peers on academic performance (Positive, Neutral, Negative).</td>
    </tr>
    <tr>
      <td>15</td>
      <td>Physical_Activity</td>
      <td>Average number of hours of physical activity per week.</td>
    </tr>
    <tr>
      <td>16</td>
      <td>Learning_Disabilities</td>
      <td>Presence of learning disabilities (Yes, No).</td>
    </tr>
    <tr>
      <td>17</td>
      <td>Parental_Education_Level</td>
      <td>Highest education level of parents (High School, College, Postgraduate).</td>
    </tr>
    <tr>
      <td>18</td>
      <td>Distance_from_Home</td>
      <td>Distance from home to school (Near, Moderate, Far).</td>
    </tr>
    <tr>
      <td>19</td>
      <td>Gender</td>
      <td>Gender of the student (Male, Female).</td>
    </tr>
    <tr>
      <td>20</td>
      <td>Exam_Score</td>
      <td>Final exam score.</td>
    </tr>
  </tbody>
</table>


## About the DataSet
The data is sourced from <a href="https://www.kaggle.com/datasets/spscientist/students-performance-in-exams/">Kaggle</a>. The data is a <em>synthetic</em> dataset meant for skills-training purposes. 

## Contributors 
The original RMD file was in conjunction with Ekene Ikeora, Agyei Osei Duodu, and Stephen Opoku Bonsu. 

## Analysis 
We perfomed multi-linear regression analysis to determine the impact of each independent variable to the mobility of the dependent variable using R programming language.  

## Conclusions 
We conclude that Hours Studied, Attendance (%), Access to Resources, Parental Involvement, and Previous Scores have statistically significant effects on the outcome of Exam Scores, with p-values less than 2×10-16. The overall model is significant and explains 85.8% of the variance in the Exam Score. To quantify their contribution towards the resulting exam score, for every; extra hour studied, there is a 0.291% increase in the exam score, extra (%) Attendance, there is a 0.199% increase in the exam score, increase in access to resources (from low to medium to high), exam scores improve by 0.962%, additional parental involvement (from low to medium to high), there is a 0.982% increase in the exam score, extra (%) in the previous scores, there is a 0.047% increase in the exam score, given that all the other variables remain constant for each of these cases.

## Future Steps 
<ol>
  <li>Use real-life dataset</li>
  <li>Expand findings with a literature review</li>
</ol>
