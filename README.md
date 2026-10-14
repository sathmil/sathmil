hi, i'm sathmi 👋

i'm a pre-med student at stanford studying computer science and computational biology. i'm drawn to clinical machine learning: making sense of body data (sleep, physiology, wearables) and building models that clinicians can actually trust.

before i wrote software, i was a storyteller and a researcher. i founded who we are to amplify underrepresented voices, and i measured and interviewed Indigenous communities in sri lanka for anthropological research. that work showed me how easily data leaves people out: a dataset that doesn't represent a population can't serve it. that idea still shapes how i build.

the question i keep coming back to: **how do you know a model works for *every* patient, not just on average?**

### featured work

**[somnivore validation](https://github.com/sathmil/somnivore-validation)** · heller laboratory, stanford
i validated an ml sleep-stage classifier on eeg/emg recordings against expert annotation across 2m+ epochs from 47 recordings. overall it looked great: 93.7% agreement, cohen's κ = 0.88. but per-stage sensitivity/specificity, mixed-effects models and time-binned analyses showed a state-dependent collapse, with rem accuracy falling from 77% to 19% at the highest apamin dose. the aggregate score had hidden it. this project is why i care about evaluation.

**[stackd](https://github.com/sathmil/stackd)** · [live app →](https://www.getstackd.app/)
a social discovery platform that turns scattered reviews of supplements, functional foods and wellness products into structured, personal recommendations. i built it solo, from zero to one.
* postgres schema that scores every product variant independently, with supabase auth and row-level security
* multi-dimensional ratings (taste, effectiveness, ingredient quality, value) and a social graph that shows friends' ratings first
* ingredient-analysis pipeline with the openai api, scoring 432 product variants across brands

### other work

* **veris** (dpl holdings): backend for an ai-powered workspace that helps judicial professionals work through case files and draft grounded responses. it's decision support in a high-stakes domain where the humans stay in charge.
* **kidney disease research** (stanford, center for tubulointerstitial kidney disease): research proposals and public-health outreach on ckdu.
* **craniofacial morphometrics** (university of kelaniya): built an original dataset from sri lanka's Indigenous communities. first-author paper in the *international journal of morphology*.
* **[tried & told](https://github.com/sathmil/tried-told)**: a learning project for understanding hybrid retrieval (bm25 + dense embeddings) piece by piece.
* **who we are**: founder of a storytelling platform with 50+ narratives from contributors in 7+ countries, featured in the sunday times.

### what i care about

* clinical ml and prediction, especially from physiological and wearable data
* model validation, evaluation and fairness: catching failures that averages hide
* llm agents and clinical decision support
* responsible ai deployment and the infrastructure that makes it work in practice
* multimodal ai for health
* sleep, nutrition and human performance

### right now

* cs106b section leader
* going deeper on clinical ml and model evaluation

### about how i work

i learn fast, i love unfamiliar problems, and i do well with high ownership. when i take something on, i keep going until i've figured it out, and i'm happy to contribute wherever i'm needed.

### connect

[linkedin](https://linkedin.com/in/sathmi) · [sathmi@stanford.edu](mailto:sathmi@stanford.edu)
