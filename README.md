# Ancient-DNA-with GPU (Tensorflow 2.1)

However, modern contamination is a big issue in Ancient DNA research area. Svante Pääbo, the founder of paleogenetics, admitted to have sequenced mostly modern DNA (presumably his own) in his famous work about DNA from a Egyptian mummy that gave rise to the field. Indeed, by just looking at modern and ancient sequences you would never guess which one came from the past. Therefore researchers in this area use advanced statistical analysis such as deamination pattern inference, where mapDamage tool is very handy. However, the problem with deamination analysis is that it is based on averaging across thousands and millions of aligned sequences, therefore it is only feasible if you have a deeply sequenced (a lot of ancient DNA needed) sample and a reference genome to get the sequences aligned to the genome which is not always available.

This is exactly where we can utilize the power of Machine and Deep Learning for detecting DNA motifs typical for ancient and modern sequences.
