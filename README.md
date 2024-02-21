<img src="https://github.com/heayounchoi/VGGNet/assets/118031423/c727a962-322d-404a-ac61-94dd422fbb82" width="50%" height="50%">
<img src="https://github.com/heayounchoi/VGGNet/assets/118031423/0c1dfec2-aa4a-4c9b-98ea-03c1f461b29e" width="50%" height="50%">
<p>test accuracy: 93.4%</p>
<br>

#### best configuration
<table>
  <tr>
    <th>batch size</th>
    <th>fc layer</th>
    <th>average pooling layer</th>
    <th>base learning rate</th>
    <th>weight decay</th>
    <th>nesterov</th>
    <th>scheduler</th>
    <th>epochs</th>
  </tr>
  <tr align="center">
    <td>128</td>
    <td>only classifier</td>
    <td>yes</td>
    <td>0.1</td>
    <td>5e-4</td>
    <td>false</td>
    <td>CosineAnnealingLR</td>
    <td>200</td>
  </tr>
</table>

#### main configuration
<table>
  <tr>
    <th>batch size</th>
    <th>fc layer</th>
    <th>average pooling layer</th>
    <th>base learning rate</th>
    <th>weight decay</th>
    <th>nesterov</th>
    <th>scheduler</th>
    <th>epochs</th>
  </tr>
  <tr align="center">
    <td>128</td>
    <td>only classifier</td>
    <td>yes</td>
    <td>0.1</td>
    <td>5e-4</td>
    <td>true</td>
    <td>CosineAnnealingLR</td>
    <td>200</td>
  </tr>
</table>
<img width="80%" alt="image" src="https://github.com/heayounchoi/VGGNet-CIFAR10/assets/118031423/b31cbd96-36e4-42a6-8470-9a216f6ad564">

