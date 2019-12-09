# formality style transfer with shared latent space

## 1. model outputs

The outputs of our methods is under the "**model_outputs**" directory. The "**EM_Out**" means the result for "**Entertainment&Music**". The "**FR_Out**" means the result for "**Family&Relationships**".

"**formal.sls_rnn**" is the result of "**S2S-SLS(RNN)**"

"**formal.sls_rnn_cmb**" is the result of "**S2S-SLS(RNN)-Combined**"

"**formal.sls_gpt**" is the result of "**S2S-SLS(GPT)**"

"**formal.gpt_ft**" is the result of "**GPT-Finetune**"

"**formal.our_nmt_cmb**" is the result of "**NMT-Combined\***".

"**formal.our_pbmt_cmb**" is the result of "**PBMT-Combined\***".

We also provide the outputs of ablation test.

## 2. model scripts

We will add a description soon.

## 3. training data<div id="contact"></div>

The training data includes original GYAFC dataset, the outputs of a simple rule based system and the psesudo-parallel data. To obtain our training data, you should first get the access to [GYAFC dataset](https://github.com/raosudha89/GYAFC-corpus). Once you have gained the access to GYAFC dataset, please forward the acknowledgment to the anonymous email address(anonymousfordoubleblindreview@gmail.com), then we will provide access to our training data for reproducing our method. Please keep anonymous in your email during double-blind review of ACL2020.

## 4. run

Please see "main.py" for the details. 

We suggest to use Pycharm to run this project.

