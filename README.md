# MLPerf Inference Visualization Template

If you have a [run](https://raw.githubusercontent.com/GATEOverflow/inference_results_v4.1/main/run.sh) script, just run that in the root of your MLPerf inference_results repository.

```
INFERENCE_RESULTS_REPO_OWNER=${{ github.repository_owner }} bash run.sh
```

This will copy the template code including CSS/HTML overrides and the JS files from this template repository to the docs site of the inference results repository.


