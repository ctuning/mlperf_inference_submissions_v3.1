This experiment is generated using [MLCommons CM](https://github.com/mlcommons/ck)
## CM Run Command
```
cm run script \
	--tags=generate-run-cmds,inference,_submission,_all-scenarios \
	--model=resnet50 \
	--implementation=reference \
	--device=cpu \
	--backend=onnxruntime \
	--category=edge \
	--division=closed \
	--quiet \
	--results_dir=/home/ec2-user/results_dir \
	--skip_submission_generation=yes \
	--execution-mode=valid
```