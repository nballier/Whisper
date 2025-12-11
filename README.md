# Whisper dictionaries

These .json files are extractions of the Whisper dictionaries of tokens, as described in Radford et al. (2023). We call them 'subtokens' in [this paper]([https://aclanthology.org/2024.icnlsp-1.15.pdf]): 
Ballier, N., Burin, L., Namdarzadeh, B., Ng, S. B., Wright, R., & Yunès, J. B. (2024). Probing whisper predictions for French, English and Persian transcriptions. In *Proceedings of the 7th International Conference on Natural Language and Speech Processing (ICNLSP 2024)* (pp. 129-138).




The files are transformations of the token dictionaries extracted using a customised implementation of Whisper available on this github <https://github.com/jbyunes/whisper.cpp>. 

WhisperSubtokensDictionary.json : a .JSON file with the Whisper IDs and the subtoken strings from Whisper's multilingual models.

MultilingualCandidates.json : a .JSON file with the Whisper IDs and the subtoken strings from Whisper's English only models.

MultilingualCandidates.json :  a .JSON file with the Whisper IDs and the 20778 multilingual subtokens for 99 languages (it is a substraction of the Multilingual dictionary minus the subtokens present in the English model).




If you use this resource, please cite our paper:

@article{ballier2024whisper,
  title={Whisper for L2 speech scoring},
  author={Ballier, Nicolas and Arnold, Taylor and M{\'e}li, Adrien and Thurston, Tori and Yun{\`e}s, Jean-Baptiste},
  journal={International Journal of Speech Technology},
  pages={923-934},
  doi={https://doi.org/10.1007/s10772-024-10141-5},
  year={2024},
  publisher={Springer}
}


