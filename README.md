# An empirical evaluation of tinyML architectures for  Class-Incremental Continual Learning
## Data Efficiency
### CIFAR-10
Impact of different number of elements in the replay buffer on different models on CIFAR-10.
<div style="display: flex; flex-wrap: wrap; justify-content: space-between;">
    <img src="Images/CIFAR10_Ele_0.8-0.75-8 PhiNet DS.png" alt="Image 1" style="width: 49%;">
    <img src="Images/CIFAR10_Ele_0.9-0.5-4 PhiNet DS.png" alt="Image 2" style="width: 49%;">
    <img src="Images/CIFAR10_Ele_0.9-0.5-4 PhiNetDS DE.png" alt="Image 3" style="width: 49%;">
    <img src="Images/CIFAR10_Ele_1.2-0.5-6 PhiNet DS.png" alt="Image 4" style="width: 49%;">
    <img src="Images/CIFAR10_Ele_MobileNetV1.png" alt="Image 5" style="width: 49%;">
    <img src="Images/CIFAR10_Ele_MobileNetV2.png" alt="Image 6" style="width: 49%;">
    <img src="Images/CIFAR10_Ele_0.75 MobileNetV2.png" alt="Image 7" style="width: 49%;">
</div>

### CORe50
Impact of different number of elements in the replay buffer on different models on CORe50.
<div style="display: flex; justify-content: space-between;">
    <img src="Images/CORe50_Ele_0.8-0.75-8 PhiNet DS.png" alt="Image 1" style="width: 49%;">
    <img src="Images/CORe50_Ele_0.9-0.5-4 PhiNet DS.png" alt="Image 2" style="width: 49%;">
    <img src="Images/CORe50_Ele_0.9-0.5-4 PhiNetDS DE.png" alt="Image 3" style="width: 49%;">
    <img src="Images/CORe50_Ele_1.2-0.5-6 PhiNet DS.png" alt="Image 4" style="width: 49%;">
    <img src="Images/CORe50_Ele_MobileNetV1.png" alt="Image 5" style="width: 49%;">
    <img src="Images/CORe50_Ele_MobileNetV2.png" alt="Image 6" style="width: 49%;">
    <img src="Images/CORe50_Ele_0.75 MobileNetV2.png" alt="Image 7" style="width: 49%;">
</div>

## Memory Evaluation
Comparison of the latent activation size and MAC of the selected layer between different models. Dimensions refer to a single sample.

<div style="display: flex; justify-content: space-between;">
    <img src="Images/MACsVSLatentSize.png" alt="Image 1" style="width: 70%;">
</div>

## Memory-Performance Trade-off Evaluation
### CIFAR-10
Performance comparison on CIFAR-10 dataset using different models and fixed maximum value for the replay buffer.
<div style="display: flex; justify-content: space-between;">
    <img src="Images/CIFAR10_0.5.png" alt="Image 1" style="width: 49%;">
    <img src="Images/CIFAR10_2.png" alt="Image 2" style="width: 49%;">
    <img src="Images/CIFAR10_5.png" alt="Image 3" style="width: 49%;">
    <img src="Images/CIFAR10_10.png" alt="Image 4" style="width: 49%;">
    <img src="Images/CIFAR10_20.png" alt="Image 5" style="width: 49%;">
    <img src="Images/CIFAR10_50.png" alt="Image 6" style="width: 49%;">
    <img src="Images/CIFAR10_100.png" alt="Image 7" style="width: 49%;">
</div>

Evaluation of the models on CIFAR-10 using different maximum values for the replay buffer.
<div style="display: flex; justify-content: space-between;">
    <img src="Images/CIFAR10_0.8-0.75-8 PhiNet DS.png" alt="Image 1" style="width: 49%;">
    <img src="Images/CIFAR10_0.9-0.5-4 PhiNet DS.png" alt="Image 2" style="width: 49%;">
    <img src="Images/CIFAR10_0.9-0.5-4 PhiNetDS DE.png" alt="Image 3" style="width: 49%;">
    <img src="Images/CIFAR10_1.2-0.5-6 PhiNet DS.png" alt="Image 4" style="width: 49%;">
    <img src="Images/CIFAR10_MobileNetV1.png" alt="Image 5" style="width: 49%;">
    <img src="Images/CIFAR10_MobileNetV2.png" alt="Image 6" style="width: 49%;">
    <img src="Images/CIFAR10_0.75 MobileNetV2.png" alt="Image 7" style="width: 49%;">
</div>

### CORe50
Performance comparison on CORe50 dataset using different models and fixed maximum value for the replay buffer.
<div style="display: flex; justify-content: space-between;">
    <img src="Images/CORe50_0.5.png" alt="Image 1" style="width: 49%;">
    <img src="Images/CORe50_2.png" alt="Image 2" style="width: 49%;">
    <img src="Images/CORe50_5.png" alt="Image 3" style="width: 49%;">
    <img src="Images/CORe50_10.png" alt="Image 4" style="width: 49%;">
    <img src="Images/CORe50_20.png" alt="Image 5" style="width: 49%;">
    <img src="Images/CORe50_50.png" alt="Image 6" style="width: 49%;">
    <img src="Images/CORe50_100.png" alt="Image 7" style="width: 49%;">
</div>

Evaluation of the models on CORe50 using different maximum values for the replay buffer.
<div style="display: flex; justify-content: space-between;">
    <img src="Images/CORe50_0.8-0.75-8 PhiNet DS.png" alt="Image 1" style="width: 49%;">
    <img src="Images/CORe50_0.9-0.5-4 PhiNet DS.png" alt="Image 2" style="width: 49%;">
    <img src="Images/CORe50_0.9-0.5-4 PhiNetDS DE.png" alt="Image 3" style="width: 49%;">
    <img src="Images/CORe50_1.2-0.5-6 PhiNet DS.png" alt="Image 4" style="width: 49%;">
    <img src="Images/CORe50_MobileNetV1.png" alt="Image 5" style="width: 49%;">
    <img src="Images/CORe50_MobileNetV2.png" alt="Image 6" style="width: 49%;">
    <img src="Images/CORe50_0.75 MobileNetV2.png" alt="Image 7" style="width: 49%;">
</div>

### Summary 
<table class="tg">
<thead>
  <tr>
    <th class="tg-wa1i" rowspan="2">Model</th>
    <th class="tg-wa1i" rowspan="2">Memory [MB]</th>
    <th class="tg-wa1i" colspan="2">CIFAR10</th>
    <th class="tg-wa1i" colspan="2">CORe50</th>
  </tr>
  <tr>
    <th class="tg-yla0">Avg. Accuracy</th>
    <th class="tg-yla0">MACs</th>
    <th class="tg-yla0">Avg. Accuracy</th>
    <th class="tg-yla0">MACs</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-cly1">PhiNet A</td>
    <td class="tg-nrix" rowspan="7">0.5</td>
    <td class="tg-nrix">50.25%</td>
    <td class="tg-nrix">3,050</td>
    <td class="tg-nrix">51.42%</td>
    <td class="tg-nrix">3,050</td>
  </tr>
  <tr>
    <td class="tg-cly1">PhiNet B</td>
    <td class="tg-nrix">48.48%</td>
    <td class="tg-nrix">3,450</td>
    <td class="tg-nrix">47.19%</td>
    <td class="tg-nrix">3,450</td>
  </tr>
  <tr>
    <td class="tg-cly1">PhiNet B<sub>9</sub></td>
    <td class="tg-nrix">51.00%</td>
    <td class="tg-nrix">3,450</td>
    <td class="tg-nrix">48.51%</td>
    <td class="tg-nrix">3,450</td>
  </tr>
  <tr>
    <td class="tg-cly1">PhiNet C</td>
    <td class="tg-nrix">47.96%</td>
    <td class="tg-nrix">4,650</td>
    <td class="tg-nrix">46.95%</td>
    <td class="tg-nrix">4,650</td>
  </tr>
  <tr>
    <td class="tg-cly1">MobileNetV1</td>
    <td class="tg-nrix">32.29%</td>
    <td class="tg-nrix">51,200</td>
    <td class="tg-nrix">23.11%</td>
    <td class="tg-nrix">51,200</td>
  </tr>
  <tr>
    <td class="tg-cly1">MobileNetV2</td>
    <td class="tg-nrix">37.01%</td>
    <td class="tg-nrix">43,092,800</td>
    <td class="tg-nrix">46.51%</td>
    <td class="tg-nrix">20,085,760</td>
  </tr>
  <tr>
    <td class="tg-cly1">0.75 MobileNetV2</td>
    <td class="tg-nrix">46.53%</td>
    <td class="tg-nrix">28,089,840</td>
    <td class="tg-nrix">45.93%</td>
    <td class="tg-nrix">28,089,840</td>
  </tr>
  <tr>
    <td class="tg-cly1">PhiNet A</td>
    <td class="tg-nrix" rowspan="7">2</td>
    <td class="tg-nrix">72.49%</td>
    <td class="tg-nrix">3,050</td>
    <td class="tg-nrix">70.20%</td>
    <td class="tg-nrix">3,050</td>
  </tr>
  <tr>
    <td class="tg-cly1">PhiNet B</td>
    <td class="tg-nrix">63.83%</td>
    <td class="tg-nrix">3,450</td>
    <td class="tg-nrix">63.73%</td>
    <td class="tg-nrix">3,450</td>
  </tr>
  <tr>
    <td class="tg-cly1">PhiNet B<sub>9</sub></td>
    <td class="tg-nrix">66.45%</td>
    <td class="tg-nrix">3,450</td>
    <td class="tg-nrix">65.10%</td>
    <td class="tg-nrix">3,450</td>
  </tr>
  <tr>
    <td class="tg-cly1">PhiNet C</td>
    <td class="tg-nrix">69.58%</td>
    <td class="tg-nrix">4,650</td>
    <td class="tg-nrix">65.65%</td>
    <td class="tg-nrix">4,650</td>
  </tr>
  <tr>
    <td class="tg-cly1">MobileNetV1</td>
    <td class="tg-nrix">32.15%</td>
    <td class="tg-nrix">51,200</td>
    <td class="tg-nrix">23.24%</td>
    <td class="tg-nrix">51,200</td>
  </tr>
  <tr>
    <td class="tg-cly1">MobileNetV2</td>
    <td class="tg-nrix">61.21%</td>
    <td class="tg-nrix">43,092,800</td>
    <td class="tg-nrix">68.99%</td>
    <td class="tg-nrix">43,092,800</td>
  </tr>
  <tr>
    <td class="tg-cly1">0.75 MobileNetV2</td>
    <td class="tg-nrix">65.18%</td>
    <td class="tg-nrix">28,089,840</td>
    <td class="tg-nrix">66.26%</td>
    <td class="tg-nrix">28,089,840</td>
  </tr>
  <tr>
    <td class="tg-cly1">PhiNet A</td>
    <td class="tg-nrix" rowspan="7">5</td>
    <td class="tg-nrix">77.82%</td>
    <td class="tg-nrix">3,050</td>
    <td class="tg-nrix">77.23%</td>
    <td class="tg-nrix">3,050</td>
  </tr>
  <tr>
    <td class="tg-cly1">PhiNet B</td>
    <td class="tg-nrix">66.34%</td>
    <td class="tg-nrix">3,450</td>
    <td class="tg-nrix">67.28%</td>
    <td class="tg-nrix">3,450</td>
  </tr>
  <tr>
    <td class="tg-cly1">PhiNet B<sub>9</sub></td>
    <td class="tg-nrix">69.80%</td>
    <td class="tg-nrix">3,450</td>
    <td class="tg-nrix">67.92%</td>
    <td class="tg-nrix">3,450</td>
  </tr>
  <tr>
    <td class="tg-cly1">PhiNet C</td>
    <td class="tg-nrix">72.78%</td>
    <td class="tg-nrix">4,650</td>
    <td class="tg-nrix">71.68%</td>
    <td class="tg-nrix">4,650</td>
  </tr>
  <tr>
    <td class="tg-cly1">MobileNetV1</td>
    <td class="tg-nrix">44.24%</td>
    <td class="tg-nrix">51,200</td>
    <td class="tg-nrix">36.77%</td>
    <td class="tg-nrix">77,806,080</td>
  </tr>
  <tr>
    <td class="tg-cly1">MobileNetV2</td>
    <td class="tg-nrix">67.16%</td>
    <td class="tg-nrix">43,092,800</td>
    <td class="tg-nrix">77.14%</td>
    <td class="tg-nrix">43,092,800</td>
  </tr>
  <tr>
    <td class="tg-cly1">0.75 MobileNetV2</td>
    <td class="tg-nrix">71.76%</td>
    <td class="tg-nrix">28,089,840</td>
    <td class="tg-nrix">77.00%</td>
    <td class="tg-nrix">28,089,840</td>
  </tr>
  <tr>
    <td class="tg-cly1">PhiNet A</td>
    <td class="tg-nrix" rowspan="7">10</td>
    <td class="tg-nrix">79.83%</td>
    <td class="tg-nrix">3,050</td>
    <td class="tg-nrix">79.04%</td>
    <td class="tg-nrix">3,050</td>
  </tr>
  <tr>
    <td class="tg-cly1">PhiNet B</td>
    <td class="tg-nrix">68.11%</td>
    <td class="tg-nrix">3,450</td>
    <td class="tg-nrix">69.58%</td>
    <td class="tg-nrix">3,450</td>
  </tr>
  <tr>
    <td class="tg-cly1">PhiNet B<sub>9</sub></td>
    <td class="tg-nrix">71.95%</td>
    <td class="tg-nrix">3,450</td>
    <td class="tg-nrix">71.69%</td>
    <td class="tg-nrix">3,450</td>
  </tr>
  <tr>
    <td class="tg-cly1">PhiNet C</td>
    <td class="tg-nrix">76.77%</td>
    <td class="tg-nrix">4,650</td>
    <td class="tg-nrix">79.26%</td>
    <td class="tg-nrix">4,650</td>
  </tr>
  <tr>
    <td class="tg-cly1">MobileNetV1</td>
    <td class="tg-nrix">53.77%</td>
    <td class="tg-nrix">51,200</td>
    <td class="tg-nrix">47.76%</td>
    <td class="tg-nrix">51,200</td>
  </tr>
  <tr>
    <td class="tg-cly1">MobileNetV2</td>
    <td class="tg-nrix">75.30%</td>
    <td class="tg-nrix">43,092,800</td>
    <td class="tg-nrix">81.89%</td>
    <td class="tg-nrix">43,092,800</td>
  </tr>
  <tr>
    <td class="tg-cly1">0.75 MobileNetV2</td>
    <td class="tg-nrix">77.23%</td>
    <td class="tg-nrix">28,089,840</td>
    <td class="tg-nrix">81.15%</td>
    <td class="tg-nrix">28,089,840</td>
  </tr>
  <tr>
    <td class="tg-cly1">PhiNet A</td>
    <td class="tg-nrix" rowspan="7">20</td>
    <td class="tg-nrix">81.88%</td>
    <td class="tg-nrix">3,050</td>
    <td class="tg-nrix">82.41%</td>
    <td class="tg-nrix">26,554,002</td>
  </tr>
  <tr>
    <td class="tg-cly1">PhiNet B</td>
    <td class="tg-nrix">73.06%</td>
    <td class="tg-nrix">5,068,714</td>
    <td class="tg-nrix">71.90%</td>
    <td class="tg-nrix">3,450</td>
  </tr>
  <tr>
    <td class="tg-cly1">PhiNet B<sub>9</sub></td>
    <td class="tg-nrix">75.82%</td>
    <td class="tg-nrix">7,833,578</td>
    <td class="tg-nrix">75.56%</td>
    <td class="tg-nrix">7,833,578</td>
  </tr>
  <tr>
    <td class="tg-cly1">PhiNet C</td>
    <td class="tg-nrix">77.10%</td>
    <td class="tg-nrix">4,650</td>
    <td class="tg-nrix">81.10%</td>
    <td class="tg-nrix">4,650</td>
  </tr>
  <tr>
    <td class="tg-cly1">MobileNetV1</td>
    <td class="tg-nrix">62.74%</td>
    <td class="tg-nrix">51,200</td>
    <td class="tg-nrix">57.88%</td>
    <td class="tg-nrix">51,200</td>
  </tr>
  <tr>
    <td class="tg-cly1">MobileNetV2</td>
    <td class="tg-nrix">81.74%</td>
    <td class="tg-nrix">43,092,800</td>
    <td class="tg-nrix">86.90%</td>
    <td class="tg-nrix">43,092,800</td>
  </tr>
  <tr>
    <td class="tg-cly1">0.75 MobileNetV2</td>
    <td class="tg-nrix">81.88%</td>
    <td class="tg-nrix">28,089,840</td>
    <td class="tg-nrix">85.85%</td>
    <td class="tg-nrix">87,691,008</td>
  </tr>
  <tr>
    <td class="tg-cly1">PhiNet A</td>
    <td class="tg-nrix" rowspan="7">50</td>
    <td class="tg-nrix">83.27%</td>
    <td class="tg-nrix">3,050</td>
    <td class="tg-nrix">86.19%</td>
    <td class="tg-nrix">26,554,002</td>
  </tr>
  <tr>
    <td class="tg-cly1">PhiNet B</td>
    <td class="tg-nrix">79.41%</td>
    <td class="tg-nrix">5,068,714</td>
    <td class="tg-nrix">75.19%</td>
    <td class="tg-nrix">12,197,466</td>
  </tr>
  <tr>
    <td class="tg-cly1">PhiNet B<sub>9</sub></td>
    <td class="tg-nrix">81.86%</td>
    <td class="tg-nrix">7,833,578</td>
    <td class="tg-nrix">79.37%</td>
    <td class="tg-nrix">31,255,778</td>
  </tr>
  <tr>
    <td class="tg-cly1">PhiNet C</td>
    <td class="tg-nrix">81.72%</td>
    <td class="tg-nrix">13,354,858</td>
    <td class="tg-nrix">83.16%</td>
    <td class="tg-nrix">31,930,098</td>
  </tr>
  <tr>
    <td class="tg-cly1">MobileNetV1</td>
    <td class="tg-nrix">68.88%</td>
    <td class="tg-nrix">51,200</td>
    <td class="tg-nrix">68.68%</td>
    <td class="tg-nrix">51,200</td>
  </tr>
  <tr>
    <td class="tg-cly1">MobileNetV2</td>
    <td class="tg-nrix">85.86%</td>
    <td class="tg-nrix">43,092,800</td>
    <td class="tg-nrix">92.51%</td>
    <td class="tg-nrix">147,774,464</td>
  </tr>
  <tr>
    <td class="tg-cly1">0.75 MobileNetV2</td>
    <td class="tg-nrix">85.27%</td>
    <td class="tg-nrix">28,089,840</td>
    <td class="tg-nrix">89.99%</td>
    <td class="tg-nrix">87,691,008</td>
  </tr>
  <tr>
    <td class="tg-cly1">PhiNet A</td>
    <td class="tg-nrix" rowspan="7">100</td>
    <td class="tg-nrix">86.69%</td>
    <td class="tg-nrix">26,554,002</td>
    <td class="tg-nrix">88.62%</td>
    <td class="tg-nrix">26,554,002</td>
  </tr>
  <tr>
    <td class="tg-cly1">PhiNet B</td>
    <td class="tg-nrix">81.60%</td>
    <td class="tg-nrix">12,197,466</td>
    <td class="tg-nrix">79.01%</td>
    <td class="tg-nrix">12,197,466</td>
  </tr>
  <tr>
    <td class="tg-cly1">PhiNet B<sub>9</sub></td>
    <td class="tg-nrix">83.48%</td>
    <td class="tg-nrix">7,833,578</td>
    <td class="tg-nrix">79.74%</td>
    <td class="tg-nrix">31,255,778</td>
  </tr>
  <tr>
    <td class="tg-cly1">PhiNet C</td>
    <td class="tg-nrix">85.25%</td>
    <td class="tg-nrix">13,354,858</td>
    <td class="tg-nrix">86.35%</td>
    <td class="tg-nrix">31,930,098</td>
  </tr>
  <tr>
    <td class="tg-cly1">MobileNetV1</td>
    <td class="tg-nrix">69.98%</td>
    <td class="tg-nrix">51,200</td>
    <td class="tg-nrix">75.93%</td>
    <td class="tg-nrix">77,806,080</td>
  </tr>
  <tr>
    <td class="tg-cly1">MobileNetV2</td>
    <td class="tg-nrix">87.49%</td>
    <td class="tg-nrix">147,774,464</td>
    <td class="tg-nrix">94.21%</td>
    <td class="tg-nrix">147,774,464</td>
  </tr>
  <tr>
    <td class="tg-cly1">0.75 MobileNetV2</td>
    <td class="tg-nrix">88.14%</td>
    <td class="tg-nrix">87,691,008</td>
    <td class="tg-nrix">91.99%</td>
    <td class="tg-nrix">87,691,008</td>
  </tr>
</tbody>
</table>
