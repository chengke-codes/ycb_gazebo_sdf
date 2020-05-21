# SDF models of YCB objects

![image.png](https://i.loli.net/2020/03/12/72kZrvPyCAQqRDt.png)

I created SDF models of most YCB objects to make them available in Gazebo. All models with textures use *Google 64k* data, models without textures are from *Poisson reconstruction*. Not all YCB objects are available here, and downloading them is slow, even with small files. However, most of them work perfectly. A detailed list of YCB data can be found at [http://ycb-benchmarks.s3-website-us-east-1.amazonaws.com/](http://ycb-benchmarks.s3-website-us-east-1.amazonaws.com/)

## How to use?

Just clone this repo in somewhere, then copy all directories to `~/.gazebo/models`. Restart your Gazebo and enjoy.

## Change Log
### 2020-05-21
1. Adjust friction to reduce model drift and shaking.