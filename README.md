Speech Understanding
========================

## Overview
This is an API package for the Speech Understanding. It allows you to expand your own application easily.  
This repository contains a sample project illustrating usage of [Speech Understanding API][hatsuwa_api]　by [docomo Developper support][dds].

## Features  

Speech Understanding API users received function name and value that used in the function when you input text.  

This API corresponds Japanese and English.   
Between Japanese and English version, there are different command list and slot list. English version doesn't have "types".   


## Usage

The speech understanding API takes input of an uttered sentence in text format and returns a function as the most-likely sought-afer feedback. You can ask a question using a text sentence in a natural, conversational tone.
A response includes the name of a function, which may be accompanied by characteristic words extracted from the input sentence. 

* If you would like to know more detailed information, please refer to the [references][references].

## Requirement  

This API enables easy access from Android, iOS and the web. Servers are left out from java. there's also REST support.


## Getting Started

* Clone or Download zip.  
* Register [docomo Developper support][dds] (for free) and aquire a API key.  
* Build and run the projects.


## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request


## Samples

![ScreenShot_1](https://devsite-pro.s3.amazonaws.com/contents_file/contents_1141121114003.png)
![ScreenShot_2](https://devsite-pro.s3.amazonaws.com/contents_file/contents_0141121114002.png)  

* Plan name is morphological analysis by speech understanding API When a schedule is registered with a calendar.
* That will be used as keywords in the keyword search function of trend article extraction API.
* Retrieved articles will be displayed at the bottom of the calendar.

* Over Android 3.0(Minimum Required SDK:API 11)  
* This sample project is usage of that SDKs.   
	**[Speech Understanding SDK for Android(v1.0.1)][hatsuwa_sdk]**  

## Attention  

This API does not return a real "answer" to an input sentence.  
If you want the application to display actual train transfer information in response to an input sentence  
(e.g., "I want to go to Tameike-sanno from Yokohama by train"),   
you need to make a further inqury into a search engine that provides train transfer  information by entering the words "Yokohama" and "Tameike-sanno" returned from the API.   



## Licence
Please make sure to comply with the guidelines in order to use our APIs.    
[Guidline Japanese.ver][guidline_ja]  
[MIT](https://github.com/docomoDeveloperSupport/open-sentence-sppech-understanding/LICENCE)  

## Author

[docomo Developper Support][dds]


[dds]:https://github.com/docomoDeveloppersupport "dds"
[hatsuwa_sdk]:https://dev.smt.docomo.ne.jp/?p=docs.api.page&api_docs_id=85 "Speech Understanding for Android(v1.0.1)"
[trend_sdk]:https://dev.smt.docomo.ne.jp/?p=docs.api.page&api_docs_id=26 "Trend Article Extraction for Android(v3.0.1)"
[hatsuwa_api]:https://dev.smt.docomo.ne.jp/?p=docs.api.page&api_docs_id=85 "Speech Understanding API"
[trend_api]:https://dev.smt.docomo.ne.jp/?p=docs.api.page&api_docs_id=26 "Trend Article Extraction API"
[guidline_ja]:https://dev.smt.docomo.ne.jp/?p=common_page&p_name=samplecode_policy "Guidline"
[references]:https://dev.smt.docomo.ne.jp/?p=docs.api.page&api_docs_id=81#tag01