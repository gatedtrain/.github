# gatedtrain

A prototype framework for post-training models where every result must pass a pre-registered statistical gate: the
metric, margin, sample size, and evaluation seeds are fixed before the run, and the report states PASS, FAIL, or
INCONCLUSIVE with the achieved power. Runs record which data each checkpoint consumed, so a data defect can be traced
to the checkpoints it reached.

- [`gatedtrain`](https://github.com/gatedtrain/gatedtrain): the framework, its adapter SDK and conformance kit.
- [`gatedtrain-design`](https://github.com/gatedtrain/gatedtrain-design): the design set the framework implements.
- `gatedtrain-recipe-*`: one repository per worked example (LLM, VLM, diffusion, video, speech, robotics, and
  control), each with its adapter, scripts, and the gate result of its published run.

All repositories are Apache-2.0. Names of third-party projects and products are trademarks of their owners;
gatedtrain is not affiliated with or endorsed by them.
