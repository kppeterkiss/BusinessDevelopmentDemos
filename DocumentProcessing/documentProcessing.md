

# Paid big vendor services

[Some IBM solution](https://www.ibm.com/blog/document-processing/)



[Microsoft AI Builder](https://learn.microsoft.com/en-us/ai-builder/overview) - [Ai builder for Invoices](https://youtu.be/NM1-DaYkHN8?si=cp-pUPUZNWkSLNIQ)
[Microsoft Power Automate](https://www.youtube.com/watch?v=GW5iUV2rRGQ)
[Microsoft power apps (Hu)](https://www.microsoft.com/hu-hu/power-platform/products/power-apps )
[Microsoft power apps (En)](https://www.microsoft.com/en-us/power-platform/products/power-apps)

## Free codes
[deepdoctection](https://github.com/deepdoctection/deepdoctection) - toolset with dockerisation - 

### from source

This fails - some issue with Detectron2

```
git clone https://github.com/deepdoctection/deepdoctection.git
cd deepdoctection
python -m venv ./ddenv
source ddenv/bin/activate
pip install -r requirements.txt
pip install torch
pip install ".[source-pt]"
 
```
### Docker

Aslo Fails, needs some work
```
docker pull deepdoctection/deepdoctection
```
add paths to ```./docker/pytorch-gpu/.env```:
- ```mkdir input```
- ```mkdir  cache_h    ```
- ```mkdir  dd_cache_h    ```
- 
- ```WORK_DIR``` for inputs to be processed ->~/input
   

 - ```CACHE_HOST``` for some cache->~/deepdoctection/cache
 - 


[Information extraction GitHub](https://github.com/aniruddha27/Information-Extraction-using-Python/blob/main/Information%20Extraction%20using%20Python.ipynb)

## Nanonets - examples, and invoice extraction service (paid)

[Simple methdos for single document type](https://nanonets.com/blog/how-to-extract-data-from-invoices-using-python/)


