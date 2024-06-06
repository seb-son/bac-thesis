## Questions

* use Masked Language Modeling
  
* split data into train/val before generating chunks -split before
  
* DataCollator pads (on left for generation - models usually cant generate from padding tokens):

 ## TODO : does this make sense?
collator = DataCollator(
    tokenizer["PAD_None"], pad_on_left=True, )
:param shift_labels : shift labels for autoregressive training? default is false
    
* how to feed a midi note to the generation in inference

    
