# eval_gdal.py
- 'eval_gdal.py' has been developed from the original 'eval.py' (yolact: https://github.com/dbolya/yolact)
- Please use splitted geotiff.
- The coordinates (x and y) of mask/box centroids are returned using gdal function. 
- [posX_list, posY_list, X_len_list, Y_len_list, areaBox_list, class_list,cxs, cys, areas, max_areas, arclens] for each object are evaluated using cv2, and saved as 'output/result.txt'
