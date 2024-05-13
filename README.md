# NIPS_Fair-Scheduling-with-Predictions
This code implements multiple algorithms for online scheduling on a single machine to minimize maximum stretch. Algorithms include Round-Robin(RR), Greedy-with-Rounding(GWR), Relaxed-Greedy(RG) and Adaptive-Relaxed-Greedy(ARG).
We evaluate RR, GWR, RG, and ARG on synthetic and real-world datasets in minimizing max-stretch, variance of stretch, and mean response time.

# How to use code
Dictionary tree:
``` bash
├── Fair_Scheduling_with_Predictions.ipynb
├── dataset
│   ├── out_ali.csv
│   ├── out_azure.csv
│   └── out_google.csv
```
## **Load code and database into Google Colab**
1. Start by copying the link to this GitHub repository. Open Google Colab in your web browser at colab.research.google.com.
2. In the Colab interface, click “GitHub,” enter the GitHub URL, and hit the search icon.
3. Select the repository, the branch, and the Jupyter Notebook.
4. Download all files in the "dataset" folder. Then click the "Files" button on the side panel of Colab, and upload all three CSV files. 
5. Run the codes from top to bottom.


