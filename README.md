## Welcome to OpenBhasa
OpenBhasa is a NPO that publishes data and data quality reports. Our goal is to provide datasets that can be used for benchmarking ASR/NLP systems in Indian Languages, these datasets should match realistic phone signals (compression/noise/sampling rate) and customer vocabulary. This will help us gaps like the ones mentioned in this ACL Web [paper](https://www.aclweb.org/anthology/2020.findings-emnlp.295.pdf).

## Details
Good datasets like [switchboard](https://catalog.ldc.upenn.edu/LDC97S62) and [callhome](https://catalog.ldc.upenn.edu/LDC97S42) in Indian languages are critical for building good ASR . Mimicking real world scenarios like vocab, code switching, optimal utterance length and disfluencies is critical for creating a relevant dataset . Based on our experience with millions of real calls, we have created such private datasets, unfortunately these can not be open sourced. We are now looking for partners who can help us create similar public equivalents. Unlike LDC we do not plan to monetize these public datasets, they will be more like openslr datasets.


## Status
We are in very early stages, we neither have public data, nor members at this point. By May 2021, we should have our first data reports on existing indian language public data. We are looking for organizations and members that can follow our guidelines and processes for creating relevant datasets. We need help in   

1. Tooling:  Developing and maintaining the website, annotation tools, audio collection components and other software and hardware parts
1. Annotation: Finding volunteers for annotation of the content, quality management, revalidation and other parts
1. Voice Providers: Finding volunteers who will provide their samples for data collection, volunteer selection is done keeping demography, gender and other factors. 
1. Script generation: Based on the provided vocab, utterance length and other parameters generate scripts that should be used by voice providers.

## Why Not
Why not common voice or openslr or GOI initiatives? We respect all of them, but focus and speed are two main reasons for starting this as a seperate initiative.

## References
Some popular indian language audio datasets are   
| Dataset | Language | Publisher | Summary| Notes |
| ------------- | ------------- | ------------- | ------------- | ------------- |
|[Shruti](http://cse.iitkgp.ac.in/~pabitra/shruti_corpus.html)| Bengali | IITKGP| 21.64 hours, MF split 75:25, Speaker Count: 34| Insufficient for DL, Good base for Kaldi|


## Support or Contact
For details please contact openbhasaATGoogleMailDotCom, Replace GoogleMail with common google mail suffix. Sorry about the inconvenience, but this is done to throw off page crawlers that mine emails.
