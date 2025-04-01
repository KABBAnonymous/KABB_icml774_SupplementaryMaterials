# Supplementary Materials for KABB: Knowledge-Aware Bayesian Bandits for Dynamic Expert Coordination in Multi-Agent Systems(774)

## Table S1: Ablation Study Results

<div style="display: flex; justify-content: center;">
  <table>
    <thead>
      <tr>
        <th>Method</th>
        <th>Win. (%)</th>
        <th>LC Win. (%)</th>
        <th>Cost per Instruction ($)</th>
        <th>RAS</th>
        <th>PWRS</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>KABB w/o Difficulty Scaling</td>
        <td>61.6</td>
        <td>60.1</td>
        <td>0.0015</td>
        <td>91.59</td>
        <td>58.53</td>
      </tr>
      <tr>
        <td>KABB w/o Semantic Matching</td>
        <td>59.9</td>
        <td>58.0</td>
        <td><b>0.0014</b></td>
        <td>89.37</td>
        <td>58.66</td>
      </tr>
      <tr>
        <td>KABB w/o Dependency Complexity</td>
        <td>62.7</td>
        <td>60.7</td>
        <td>0.0017</td>
        <td>91.67</td>
        <td>56.08</td>
      </tr>
      <tr>
        <td>KABB w/o Historical Effectiveness</td>
        <td>65.7</td>
        <td>62.1</td>
        <td>0.0016</td>
        <td>91.13</td>
        <td>58.46</td>
      </tr>
      <tr>
        <td>KABB w/o Team Complementarity</td>
        <td>63.1</td>
        <td>60.3</td>
        <td>0.0017</td>
        <td>92.32</td>
        <td>59.72</td>
      </tr>
      <tr>
        <td>EmbedLLM (MAB)</td>
        <td>62.9</td>
        <td>60.6</td>
        <td>0.0015</td>
        <td>93.03</td>
        <td>59.68</td>
      </tr>
      <tr>
      <td><b>KA (MAB) (i.e. KABB)</b></td>
      <td><b>66.7</b></td>
      <td><b>62.4</b></td>
      <td>0.0016</td>
      <td><b>94.16</b></td>
      <td><b>60.19</b></td>
      </tr>
    </tbody>
  </table>
</div>

## Table S2: Comparision with Other LLM Router Methods

<div style="display: flex; justify-content: center;">
<table>
<thead>
<tr>
<th>Method</th>
<th>Win. (%)</th>
<th>LC Win. (%)</th>
<th>Cost per Instruction ($)</th>
</tr>
</thead>
<tbody>
<tr>
<td>FrugalGPT</td>
<td>35.2</td>
<td>43.5</td>
<td><b>0.0005</b></td>
</tr>
<tr>
<td>EmbedLLM</td>
<td>41.4</td>
<td>48.0</td>
<td>0.0011</td>
</tr>
<tr>
<td>HybridLLM</td>
<td>38.8</td>
<td>45.4</td>
<td>0.0013</td>
</tr>
<tr>
<td><b>KABB (Ours)</b></td>
<td><b>66.7</b></td>
<td><b>62.4</b></td>
<td>0.0016</td>
</tr>
</tbody>
</table>
</div>

## Overview of KABB (Updated Figure 2 in Paper)
<div style="text-align: center;">
  <img src="d209159bd0fc1d5a8a8e968dd7424b2.png" alt="Updated Figure 2">
</div>

## Representative Visualization of Knowledge Graph
<div style="text-align: center;">
  <img src="knowledgegraph.png" alt="Updated picture of the knowledge graph">
</div>

## Table S3: Error Analysis Case 1
<div style="text-align: center;">
  <img src="6f0d0af9ed0c1a8a670b9403a9a3656.png" alt="Error analysis case 1">
</div>

## Table S4: Error Analysis Case 2
<div style="text-align: center;">
  <img src="32a90d29758a043aa1dedcaaf5dad1d.png" alt="Error analysis case 2">
</div>





