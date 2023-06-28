# ROBUSTNESS

when AI is robust it is more likely to handle exceptional conditions effectively, like abnormalities in input and malicious attacks, without causing unintetional harm

`Adversarial robustness` - this refers to AI models ability to resist being fooled.

## ADVERSIAL ATTACK

Adversarial attacks are intentionally carried out on AI systems to accomplish a malicious end goal by taking advantage of AI system vulnerabilities.

An adversarial attack aims to negatively impact the system performance, exploit data used, and corrupt the model logic. The one who takes advantage of the AI system vulnerabilities to accomplish their motive is called an adversary.

“Here, the adversary attacks the system by adding small changes called perturbations or noise to the input image. The perturbation can be minimal and imperceptible to human eyes. However, when sent to the deployed AI model, the modified image results in an undesirable or incorrect prediction.”

## TYPES OF ADVERSIAL ATTACK

1. poisioning
2. Evasion

### POISIONING

this can happen in the following ways:

1. injecting malicious samples into training data.
2. Updating features and labels of the training data
3. Modifying AI model architecture, parameters, and logic”

## EVASION

Evasion can happen after the model deployment phase in the following ways:

1. Sending malicious test samples to the deployed model
2. Corrupting test data sent to the deployed model
