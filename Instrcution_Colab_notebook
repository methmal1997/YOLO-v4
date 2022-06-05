# Here is full code file in Google colab for custom YOLO v4 algoritham.



## Instrcution

1.{optional-:  (		download destop app and run on desktop
		run destop app in cmd
		1. 'pip install tk'
		2. git clone https://github.com/Texas-Aerial-Robotics/BBox-Label-Tool.git)
Here we only needbbox.py,convet.pyprocess.py only. So you can get this project
create image, Label, Example file and include dataset in image file according class wise
run 'python bbox_tool.py' and annotage data in image file.
replace that text file into label file under class wise.
Then create ouput folder in label folder and edit path  in converter file and run it. It produce (class, center x & y, w,h) yolov4 
format in text file}

2. easy method download data and create dataset-:   https://www.youtube.com/watch?v=_4A9inxGqRM&t=666s


using one or two create download image and create annotate files (prefer method -2 )

After that create multiple image folder copy all the images and output_text file into this

Goto google colab and change settings to GPU 

run a coding to file and after pretained weight gettting deleete everything except yolov4-custom.cfg in cfg file darknet


'!chmod +x ./darknet' give permission to access darknet

after training  change custom.cfg file using
'%cd cfg
!sed -i 's/batch=64/batch=1/' yolov4-custom.cfg
!sed -i 's/subdivisions=16/subdivisions=1/' yolov4-custom.cfg
%cd ..'

prediction image shoup  jpg and please check other file format it can be jpg, jpeg or etc.

full code file
https://drive.google.com/drive/folders/1vY10kwTudVJiSvAm5DNW6P-UD4sbtaSi?usp=sharing
