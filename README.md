# Supplementary Materials for KABB: Knowledge-Aware Bayesian Bandits for Dynamic Expert Coordination in Multi-Agent Systems(774)

## Table 1: Ablation Study Results

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
        <td>0.0014</td>
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
      <td><b>0.0016</b></td>
      <td><b>94.16</b></td>
      <td><b>60.19</b></td>
      </tr>
    </tbody>
  </table>
</div>

## Table 2: Comparision with Other LLM Router Methods

<div style="display: flex; justify-content: center;">
  <table>
    <thead>
      <tr>
        <th>MODEL</th>
        <th>DATASETS</th>
        <th>FEATURE MIXER</th>
        <th>#PARAM.</th>
        <th>FLOPS</th>
        <th>TOP-1 (ORIGINAL)</th>
        <th>TOP-1 (W/ REG.)</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>ResNet/18</td>
        <td>CIFAR-10</td>
        <td>MLP</td>
        <td>11.1M</td>
        <td>0.56G</td>
        <td>91.19</td>
        <td>91.32</td>
      </tr>
      <tr>
        <td></td>
        <td></td>
        <td><b>KAF</b></td>
        <td>12.0M</td>
        <td>0.63G</td>
        <td>91.72</td>
        <td>91.88</td>
      </tr>
      <tr>
        <td></td>
        <td></td>
        <td>GPKAN</td>
        <td>11.3M</td>
        <td>0.56G</td>
        <td>90.98</td>
        <td>91.15</td>
      </tr>
      <tr>
        <td></td>
        <td></td>
        <td>FAN</td>
        <td>8M</td>
        <td>0.42G</td>
        <td>90.69</td>
        <td>90.82</td>
      </tr>
      <tr>
        <td></td>
        <td></td>
        <td><b>KAN</b></td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
      </tr>
      <tr>
        <td>MLP Mixer/S</td>
        <td>ImageNet1k</td>
        <td>MLP</td>
        <td>18.2M</td>
        <td>3.8G</td>
        <td>63.5</td>
        <td>63.7</td>
      </tr>
      <tr>
        <td></td>
        <td></td>
        <td><b>KAF</b></td>
        <td>18.8M</td>
        <td>4.2G</td>
        <td>64.7</td>
        <td>65.0</td>
      </tr>
      <tr>
        <td></td>
        <td></td>
        <td>GPKAN</td>
        <td>18.8M</td>
        <td>4.0G</td>
        <td>62.9</td>
        <td>63.2</td>
      </tr>
      <tr>
        <td></td>
        <td></td>
        <td>FAN</td>
        <td>15.7M</td>
        <td>3.2G</td>
        <td>58.2</td>
        <td>58.6</td>
      </tr>
      <tr>
        <td></td>
        <td></td>
        <td><b>KAN</b></td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
      </tr>
      <tr>
        <td>ViT-T/16</td>
        <td>ImageNet1K</td>
        <td>MLP</td>
        <td>5.7M</td>
        <td>1.08G</td>
        <td>72.3</td>
        <td>72.5</td>
      </tr>
      <tr>
        <td></td>
        <td></td>
        <td><b>KAF</b></td>
        <td>5.9M</td>
        <td>1.12G</td>
        <td>73.2</td>
        <td>73.5</td>
      </tr>
      <tr>
        <td></td>
        <td></td>
        <td>GPKAN</td>
        <td>5.7M</td>
        <td>1.13G</td>
        <td>74.6</td>
        <td>74.8</td>
      </tr>
      <tr>
        <td></td>
        <td></td>
        <td>FAN</td>
        <td>4.2M</td>
        <td>0.96G</td>
        <td>65.7</td>
        <td>66.0</td>
      </tr>
      <tr>
        <td></td>
        <td></td>
        <td><b>KAN</b></td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
      </tr>
      <tr>
        <td>MLP KAN(Deit)</td>
        <td>Cifar100</td>
        <td>MLP</td>
        <td>1.3M</td>
        <td>0.12G</td>
        <td>49.0</td>
        <td>49.3</td>
      </tr>
      <tr>
        <td></td>
        <td></td>
        <td><b>KAF</b></td>
        <td>1.4M</td>
        <td>0.15G</td>
        <td>53.8</td>
        <td>54.2</td>
      </tr>
      <tr>
        <td></td>
        <td></td>
        <td>KAN</td>
        <td>1.9M</td>
        <td>0.19G</td>
        <td>51.2</td>
        <td>51.6</td>
      </tr>
      <tr>
        <td></td>
        <td></td>
        <td>GPKAN</td>
        <td>1.4M</td>
        <td>0.14G</td>
        <td>54.3</td>
        <td>54.6</td>
      </tr>
      <tr>
        <td></td>
        <td></td>
        <td>FAN</td>
        <td>1M</td>
        <td>0.1G</td>
        <td>46.7</td>
        <td>47.1</td>
      </tr>
    </tbody>
  </table>
</div>

## Figure 1: Overview of KABB (Updated Figure 2 in Paper)
<div style="text-align: center;">
  <img src="update2.png" alt="Updated Figure 2">
</div>

## Figure 2: Representative Visualization of Knowledge Graph
<div style="text-align: center;">
  <img src="knowledgegraph.png" alt="Updated picture of the knowledge graph">
</div>

## Table 3: Error Analysis Case 1
<div style="text-align: center;">
  <img src="6f0d0af9ed0c1a8a670b9403a9a3656.png" alt="Error analysis case 1">
</div>

## Table 4: Error Analysis Case 2
<div style="text-align: center;">
  <img src="32a90d29758a043aa1dedcaaf5dad1d.png" alt="Error analysis case 2">
</div>





