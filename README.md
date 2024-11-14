# Summary

## Dataset
I have utiised a Diabestes prediction model which utilizes 18 features and 319794 subjects


  <div id="df-a2edb229-7905-44cd-8ecc-8a8f295d92f4">
    <div class="colab-df-container">
      <div>

<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>HeartDisease</th>
      <th>BMI</th>
      <th>Smoking</th>
      <th>AlcoholDrinking</th>
      <th>Stroke</th>
      <th>PhysicalHealth</th>
      <th>MentalHealth</th>
      <th>DiffWalking</th>
      <th>Sex</th>
      <th>AgeCategory</th>
      <th>Race</th>
      <th>Diabetic</th>
      <th>PhysicalActivity</th>
      <th>GenHealth</th>
      <th>SleepTime</th>
      <th>Asthma</th>
      <th>KidneyDisease</th>
      <th>SkinCancer</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>No</td>
      <td>16.60</td>
      <td>Yes</td>
      <td>No</td>
      <td>No</td>
      <td>3.0</td>
      <td>30.0</td>
      <td>No</td>
      <td>Female</td>
      <td>55-59</td>
      <td>White</td>
      <td>Yes</td>
      <td>Yes</td>
      <td>Very good</td>
      <td>5.0</td>
      <td>Yes</td>
      <td>No</td>
      <td>Yes</td>
    </tr>
    <tr>
      <th>1</th>
      <td>No</td>
      <td>20.34</td>
      <td>No</td>
      <td>No</td>
      <td>Yes</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>No</td>
      <td>Female</td>
      <td>80 or older</td>
      <td>White</td>
      <td>No</td>
      <td>Yes</td>
      <td>Very good</td>
      <td>7.0</td>
      <td>No</td>
      <td>No</td>
      <td>No</td>
    </tr>
    <tr>
      <th>2</th>
      <td>No</td>
      <td>26.58</td>
      <td>Yes</td>
      <td>No</td>
      <td>No</td>
      <td>20.0</td>
      <td>30.0</td>
      <td>No</td>
      <td>Male</td>
      <td>65-69</td>
      <td>White</td>
      <td>Yes</td>
      <td>Yes</td>
      <td>Fair</td>
      <td>8.0</td>
      <td>Yes</td>
      <td>No</td>
      <td>No</td>
    </tr>
    <tr>
      <th>3</th>
      <td>No</td>
      <td>24.21</td>
      <td>No</td>
      <td>No</td>
      <td>No</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>No</td>
      <td>Female</td>
      <td>75-79</td>
      <td>White</td>
      <td>No</td>
      <td>No</td>
      <td>Good</td>
      <td>6.0</td>
      <td>No</td>
      <td>No</td>
      <td>Yes</td>
    </tr>
    <tr>
      <th>4</th>
      <td>No</td>
      <td>23.71</td>
      <td>No</td>
      <td>No</td>
      <td>No</td>
      <td>28.0</td>
      <td>0.0</td>
      <td>Yes</td>
      <td>Female</td>
      <td>40-44</td>
      <td>White</td>
      <td>No</td>
      <td>Yes</td>
      <td>Very good</td>
      <td>8.0</td>
      <td>No</td>
      <td>No</td>
      <td>No</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>319790</th>
      <td>Yes</td>
      <td>27.41</td>
      <td>Yes</td>
      <td>No</td>
      <td>No</td>
      <td>7.0</td>
      <td>0.0</td>
      <td>Yes</td>
      <td>Male</td>
      <td>60-64</td>
      <td>Hispanic</td>
      <td>Yes</td>
      <td>No</td>
      <td>Fair</td>
      <td>6.0</td>
      <td>Yes</td>
      <td>No</td>
      <td>No</td>
    </tr>
    <tr>
      <th>319791</th>
      <td>No</td>
      <td>29.84</td>
      <td>Yes</td>
      <td>No</td>
      <td>No</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>No</td>
      <td>Male</td>
      <td>35-39</td>
      <td>Hispanic</td>
      <td>No</td>
      <td>Yes</td>
      <td>Very good</td>
      <td>5.0</td>
      <td>Yes</td>
      <td>No</td>
      <td>No</td>
    </tr>
    <tr>
      <th>319792</th>
      <td>No</td>
      <td>24.24</td>
      <td>No</td>
      <td>No</td>
      <td>No</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>No</td>
      <td>Female</td>
      <td>45-49</td>
      <td>Hispanic</td>
      <td>No</td>
      <td>Yes</td>
      <td>Good</td>
      <td>6.0</td>
      <td>No</td>
      <td>No</td>
      <td>No</td>
    </tr>
    <tr>
      <th>319793</th>
      <td>No</td>
      <td>32.81</td>
      <td>No</td>
      <td>No</td>
      <td>No</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>No</td>
      <td>Female</td>
      <td>25-29</td>
      <td>Hispanic</td>
      <td>No</td>
      <td>No</td>
      <td>Good</td>
      <td>12.0</td>
      <td>No</td>
      <td>No</td>
      <td>No</td>
    </tr>
    <tr>
      <th>319794</th>
      <td>No</td>
      <td>46.56</td>
      <td>No</td>
      <td>No</td>
      <td>No</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>No</td>
      <td>Female</td>
      <td>80 or older</td>
      <td>Hispanic</td>
      <td>No</td>
      <td>Yes</td>
      <td>Good</td>
      <td>8.0</td>
      <td>No</td>
      <td>No</td>
      <td>No</td>
    </tr>
  </tbody>
</table>
<p>319795 rows × 18 columns</p>
</div>
      <button class="colab-df-convert" onclick="convertToInteractive('df-a2edb229-7905-44cd-8ecc-8a8f295d92f4')"
              title="Convert this dataframe to an interactive table."
              style="display:none;">

        
## Loss Curve    
        
![image](https://github.com/user-attachments/assets/3db0711f-0fcc-4213-ba40-63c9ce227c3b)


## Model Accuracy

![image](https://github.com/user-attachments/assets/7bf9e89b-a266-428d-867c-1903f1c1e114)
        
## Evaluation Metrics

![image](https://github.com/user-attachments/assets/b7798878-4e06-492c-98ab-768ccee29bd3)





  
