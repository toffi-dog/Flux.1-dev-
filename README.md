## Qualitative comparison on dog erasure on FLUX.1 [dev]

• Efficacy: Unlearned prompt (e.g., "dog"). Measures exact target removal.  
• Generality: Synonym prompt (e.g., "pooch"). Measures defense against semantic bypass.  
• Specificity: Unrelated prompt (e.g., "bird"). Measures preservation of safe, baseline knowledge.  

![Example](flux_dog.jpg)

---

## Failure cases

NSFW erased  
Issues with words having multiple meanings.

Over-unlearning: Unintended distortion of safe concepts containing blocked keywords (e.g., "nude color dress", "medical anatomy").

![Failure Cases](failurecases.jpg)
