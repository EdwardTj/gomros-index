<template>
  <div id="robot-box">
    <el-container id="top-container">
      <el-row id="top-outline">
        <el-col id="top-bc" :span="13">
          <el-row type="flex" justify="start" style="padding: 10px">
            <el-col id="company-logo" :span="3">
              <img src="static/img/MobileRobot/logo1.svg" class="cl-img">
            </el-col>
            <el-col id="tc-text" :span="20">
              <p><span style="font-size: 60px" class="font_basic">GomROS</span>
                <span class="font_basic">工业基础软件</span></p>
              <p><span style="font-size: 60px" class="font_basic">机器人操作系统</span>
                <span class="font_basic">机器人系统软件</span></p>
              <p id="top_explain">
                GomROS（句芒）是一款为机器人、自动化设备等高端智能装备提供的国产原创操作系统</p>
            </el-col>
          </el-row>
        </el-col>
        <el-col id="top-bcr" :span="11">
          &nbsp;
        </el-col>
      </el-row>
      <el-footer id="top-footer">
        <p id="tf-text">什么是机器人操作系统？</p>
      </el-footer>
    </el-container>

    <div>
      <!--    第一行 什么是机器人操作系统  -->
      <el-row class="background_white" style="padding-bottom: 0">
        <el-col :span="10" style="margin-left: 80px">
          <p id="ro-text1">GomROS机器人操作系统</p>
          <p id="ro-text2">是一组软件库和工具,能够帮助您快速构建机器人应用程序。从控制程序到先进算法的集合，
            并且借助强大的开发人员工具，让您可以快速搭建机器人项目。</p>
          <p id="ro-text3">您需要的软件系统，我们已经给您封装好了，您可以随时调用。</p>
        </el-col>
        <el-col id="row-one" :span="11">
          <el-row :gutter="10" type="flex">
            <el-col
                style="width:800px;height:200px;background-image: url(static/img/MobileRobot/u21.gif);
                background-size: cover;margin-right: 2%;text-align: center;">
              <el-col :span="8">
                &nbsp;
              </el-col>
              <el-col :span="7" style="text-align: center">
                <p id="ro_img1_text">视觉识别算法</p>
              </el-col>
              <el-col :span="8">
                &nbsp;
              </el-col>
            </el-col>
            <el-col
                style="width:800px;background-image: url(static/img/RobotOperateSystem/u702.gif);
                background-size: cover;text-align: center">
              <el-col :span="8">
                &nbsp;
              </el-col>
              <el-col :span="7">
                <p id="ro_img2_text">路径规划算法</p>
              </el-col>
              <el-col :span="8">
                &nbsp;
              </el-col>
            </el-col>
          </el-row>
          <el-row :gutter="10" type="flex">
            <el-col
                style="width:800px;height:200px;background-image: url(static/img/MobileRobot/u27.gif);
                background-size: cover;margin-right: 2%;text-align: center">
              <el-col :span="8">
                &nbsp;
              </el-col>
              <el-col :span="7">
                <p id="ro_img3_text">激光导航算法</p>
              </el-col>
              <el-col :span="8">
                &nbsp;
              </el-col>
            </el-col>
            <el-col
                style="width:800px;background-image: url(static/img/RobotOperateSystem/u704.gif);
                background-size: cover;text-align: center">
              <el-col :span="8">
                &nbsp;
              </el-col>
              <el-col :span="7">
                <p id="ro_img4_text">视觉避障算法</p>
              </el-col>
              <el-col :span="8">
                &nbsp;
              </el-col>
            </el-col>
          </el-row>
        </el-col>
        <!--        <el-row>-->
        <!--          <img id="ro_down" src="static/img/RobotOperateSystem/r01.jpg">-->
        <!--        </el-row>-->
      </el-row>
      <el-row style="padding-left: 60px;padding-right: 0;padding-top: 0;padding-bottom: 10px">
        <el-col :span="12" style="border: 2px dashed #0d64e8;">
          <el-row
              style="width: 100%;height:40px;text-align: center;font-size: 14px;color: #0D64E8;font-weight: bolder;
              padding-bottom: 0;margin-top: 5px;margin-bottom: 10px;">
            移动机器人的位置、姿态、状态，关节臂姿态、状态、视觉目标位置，避障区域、障碍物尺寸、位置。
          </el-row>
          <el-row style="padding-left: 0;padding-right: 0;padding-bottom: 0">
            <el-col :sapn="2"
                    style="width: 10%;margin-left:1%;background-color: #0d64e8;border-radius:15%;text-align: center;
                    color: white;font-weight: bolder;font-size: 18px;padding-top: 14px;padding-bottom: 14px">
              数据处理
            </el-col>
            <el-col :sapn="2"
                    style="width: 10%;margin-left: 1%;border: 2px solid #0d64e8;border-radius:15%;text-align: center;
                    color: #0d64e8;font-weight: bolder;font-size: 14px;padding-top: 14px;padding-bottom: 14px">
              建图
            </el-col>
            <el-col :sapn="2"
                    style="width: 10%;margin-left: 1%;border: 2px solid #0d64e8;border-radius:15%;text-align: center;
                    color: #0d64e8;font-weight: bolder;font-size: 14px;padding-top: 14px;padding-bottom: 14px">
              定位
            </el-col>
            <el-col :sapn="2"
                    style="width: 10%;margin-left: 1%;border: 2px solid #0d64e8;border-radius:15%;text-align: center;
                    color: #0d64e8;font-weight: bolder;font-size: 14px;padding-top: 14px;padding-bottom: 14px">
              运动规划
            </el-col>
            <el-col :sapn="2"
                    style="width: 10%;margin-left: 1%;border: 2px solid #0d64e8;border-radius:15%;text-align: center;
                    color: #0d64e8;font-weight: bolder;font-size: 14px;padding-top: 14px;padding-bottom: 14px">
              坐标系变化
            </el-col>
            <el-col :sapn="2"
                    style="width: 10%;margin-left: 1%;border: 2px solid #0d64e8;border-radius:15%;text-align: center;
                    color: #0d64e8;font-weight: bolder;font-size: 14px;padding-top: 14px;padding-bottom: 14px">
              姿态预测
            </el-col>
            <el-col :sapn="2"
                    style="width: 10%;margin-left: 1%;border: 2px solid #0d64e8;border-radius:15%;text-align: center;
                    color: #0d64e8;font-weight: bolder;font-size: 14px;padding-top: 14px;padding-bottom: 14px">
              图像处理
            </el-col>
            <el-col :sapn="2"
                    style="width: 10%;margin-left: 1%;border: 2px solid #0d64e8;border-radius:15%;text-align: center;
                    color: #0d64e8;font-weight: bolder;font-size: 14px;padding-top: 14px;padding-bottom: 14px">
              特征表达
            </el-col>
            <el-col :sapn="2"
                    style="width: 10%;margin-left: 1%;border: 2px solid #0d64e8;border-radius:15%;text-align: center;
                    color: #0d64e8;font-weight: bolder;font-size: 14px;padding-top: 14px;padding-bottom: 14px">
              模型训练
            </el-col>
          </el-row>
          <el-row style="text-align: center;padding-left: 0;padding-right: 0;">
            <el-col :sapn="2" style="width: 10%;margin-left:1%;">
              &nbsp;
            </el-col>
            <el-col :sapn="2"
                    style="width: 10%;margin-left: 1%;border: 2px solid #0d64e8;border-radius:15%;text-align: center;
                    color: #0d64e8;font-weight: bolder;font-size: 14px;padding-top: 14px;padding-bottom: 14px">
              数据滤波
            </el-col>
            <el-col :sapn="2"
                    style="width: 10%;margin-left: 1%;border: 2px solid #0d64e8;border-radius:15%;text-align: center;
                    color: #0d64e8;font-weight: bolder;font-size: 14px;padding-top: 14px;padding-bottom: 14px">
              数据融合
            </el-col>
            <el-col :sapn="2"
                    style="width: 10%;margin-left: 1%;border: 2px solid #0d64e8;border-radius:15%;text-align: center;
                    color: #0d64e8;font-weight: bolder;font-size: 14px;padding-top: 14px;padding-bottom: 14px">
              数据预测
            </el-col>
            <el-col :sapn="2"
                    style="width: 10%;margin-left: 1%;border: 2px solid #0d64e8;border-radius:15%;text-align: center;
                    color: #0d64e8;font-weight: bolder;font-size: 14px;padding-top: 14px;padding-bottom: 14px">
              数据插值
            </el-col>
            <el-col :sapn="2"
                    style="width: 10%;margin-left: 1%;border: 2px solid #0d64e8;border-radius:15%;text-align: center;
                    color: #0d64e8;font-weight: bolder;font-size: 14px;padding-top: 14px;padding-bottom: 14px">
              优化算法
            </el-col>
            <el-col :sapn="2"
                    style="width: 10%;margin-left: 1%;border: 2px solid #0d64e8;border-radius:15%;text-align: center;
                    color: #0d64e8;font-weight: bolder;font-size: 14px;padding-top: 14px;padding-bottom: 14px">
              搜索算法
            </el-col>
            <el-col :sapn="2"
                    style="width: 10%;margin-left: 1%;border: 2px solid #0d64e8;border-radius:15%;text-align: center;
                    color: #0d64e8;font-weight: bolder;font-size: 14px;padding-top: 14px;padding-bottom: 14px">
              深度学习
            </el-col>
            <el-col :sapn="2" style="width: 10%;margin-left: 1%;">
              &nbsp;
            </el-col>
          </el-row>
        </el-col>
        <el-col :span="11" style="border: 2px dashed #0d64e8;margin-left: 1%">
          <el-row style="padding-bottom: 0;">
            <el-col :span="4">
              &nbsp;
            </el-col>
            <el-col :span="3"
                    style="margin-left: 1%;width: 15%;height: 40px;background-color: #0d64e8;border-radius:15%;
                    text-align: center;color: white;font-weight: bolder;font-size: 14px;padding-top:10px;padding-bottom: 10px">
              平面移动规划
            </el-col>
            <el-col :span="3"
                    style="margin-left: 2%;width: 15%;height: 40px;background-color: #0d64e8;border-radius:15%;
                    text-align: center;color: white;font-weight: bolder;font-size: 14px;padding-top:10px;padding-bottom: 10px">
              移动避障规则
            </el-col>
            <el-col :span="3"
                    style="margin-left: 2%;width: 15%;height: 40px;background-color: #0d64e8;border-radius:15%;
                    text-align: center;color: white;font-weight: bolder;font-size: 14px;padding-top:10px;padding-bottom: 10px">
              关节运动规划
            </el-col>
            <el-col :span="3"
                    style="margin-left: 2%;width: 15%;height: 40px;background-color: #0d64e8;border-radius:15%;
                    text-align: center;color: white;font-weight: bolder;font-size: 14px;padding-top:10px;padding-bottom: 10px">
              关节运动避障
            </el-col>
            <el-col :span="4">
              &nbsp;
            </el-col>
          </el-row>
          <el-row style="padding-top: 0;padding-left: 10px;padding-bottom: 0">
            <el-col :span="3"
                    style="width: 12%;background-color: #0d64e8;border-radius:15%;text-align: center;
                    color: white;font-weight: bolder;font-size: 18px;padding-top:13px;padding-bottom: 13px">
              逻辑处理
            </el-col>
            <el-col :sapn="3"
                    style="width: 12%;margin-left: 1%;border: 2px solid #0d64e8;border-radius:15%;text-align: center;
                    color: #0d64e8;font-weight: bolder;font-size: 14px;padding-top: 14px;padding-bottom: 14px">
              轨迹矫正
            </el-col>
            <el-col :sapn="3"
                    style="width: 12%;margin-left: 1%;border: 2px solid #0d64e8;border-radius:15%;text-align: center;
                    color: #0d64e8;font-weight: bolder;font-size: 14px;padding-top: 14px;padding-bottom: 14px">
              轨迹补差
            </el-col>
            <el-col :sapn="3"
                    style="width: 12%;margin-left: 1%;border: 2px solid #0d64e8;border-radius:15%;text-align: center;
                    color: #0d64e8;font-weight: bolder;font-size: 14px;padding-top: 14px;padding-bottom: 14px">
              路径搜索
            </el-col>
            <el-col :sapn="3"
                    style="width: 12%;margin-left: 1%;border: 2px solid #0d64e8;border-radius:15%;text-align: center;
                    color: #0d64e8;font-weight: bolder;font-size: 14px;padding-top: 14px;padding-bottom: 14px">
              轨迹预处理
            </el-col>
            <el-col :sapn="3"
                    style="width: 12%;margin-left: 1%;border: 2px solid #0d64e8;border-radius:15%;text-align: center;
                    color: #0d64e8;font-weight: bolder;font-size: 14px;padding-top: 14px;padding-bottom: 14px">
              速度控制
            </el-col>
            <el-col :sapn="3"
                    style="width: 12%;margin-left: 1%;border: 2px solid #0d64e8;border-radius:15%;text-align: center;
                    color: #0d64e8;font-weight: bolder;font-size: 14px;padding-top: 14px;padding-bottom: 14px">
              避障控制
            </el-col>
          </el-row>
          <el-row style="padding-left: 10px;padding-bottom: 2%">
            <el-col :span="3" style="width: 12%;">
              &nbsp;
            </el-col>
            <el-col :sapn="3"
                    style="width: 12%;margin-left: 1%;border: 2px solid #0d64e8;border-radius:15%;text-align: center;
                    color: #0d64e8;font-weight: bolder;font-size: 14px;padding-top: 14px;padding-bottom: 14px">
              绕障逻辑
            </el-col>
            <el-col :sapn="3"
                    style="width: 12%;margin-left: 1%;border: 2px solid #0d64e8;border-radius:15%;text-align: center;
                    color: #0d64e8;font-weight: bolder;font-size: 14px;padding-top: 14px;padding-bottom: 14px">
              力矩控制
            </el-col>
            <el-col :sapn="3"
                    style="width: 12%;margin-left: 1%;border: 2px solid #0d64e8;border-radius:15%;text-align: center;
                    color: #0d64e8;font-weight: bolder;font-size: 14px;padding-top: 14px;padding-bottom: 14px">
              坐标处理
            </el-col>
            <el-col :sapn="3"
                    style="width: 12%;margin-left: 1%;border: 2px solid #0d64e8;border-radius:15%;text-align: center;
                    color: #0d64e8;font-weight: bolder;font-size: 14px;padding-top: 5px;padding-bottom: 5px">
              运动模型<br>逆解
            </el-col>
            <el-col :sapn="3"
                    style="width: 12%;margin-left: 1%;border: 2px solid #0d64e8;border-radius:15%;text-align: center;
                    color: #0d64e8;font-weight: bolder;font-size: 14px;padding-top: 14px;padding-bottom: 14px">
              位置控制
            </el-col>
            <el-col :sapn="3"
                    style="width: 12%;margin-left: 1%;border: 2px solid #0d64e8;border-radius:15%;text-align: center;
                    color: #0d64e8;font-weight: bolder;font-size: 14px;padding-top: 14px;padding-bottom: 14px">
              跟踪控制
            </el-col>
          </el-row>
        </el-col>
      </el-row>
      <el-row style="padding-left: 60px;padding-right: 0px;padding-top: 0px;padding-bottom: 10px">
        <el-col :span="12" style="border: 2px dashed #0d64e8;height: 179px">
          <el-row style="height: 78px;padding-top: 15px;padding-bottom: 15px;margin-top: 2%">
            <el-col :span="3"
                    style="text-align:center;font-size: 18px;color: #0d64e8;font-weight: bolder;margin-top: 1%;margin-right: 2%">
              硬件驱动
            </el-col>
            <el-col :span="3">
              <el-row style="text-align:center;font-size: 14px;color: #0d64e8;font-weight: bolder">激光雷达</el-row>
              <el-row style="text-align:center;font-size: 14px;color: #0d64e8;font-weight: bolder">毫米波雷达</el-row>
            </el-col>
            <el-col :span="3">
              <el-row style="text-align:center;font-size: 14px;color: #0d64e8;font-weight: bolder">超声波雷达</el-row>
              <el-row style="text-align:center;font-size: 14px;color: #0d64e8;font-weight: bolder">点距离雷达</el-row>
            </el-col>
            <el-col :span="4">
              <el-row style="text-align:center;font-size: 14px;color: #0d64e8;font-weight: bolder">摄像头</el-row>
              <el-row style="text-align:center;font-size: 14px;color: #0d64e8;font-weight: bolder">3D视觉传感器</el-row>
            </el-col>
            <el-col :span="3">
              <el-row style="text-align:center;font-size: 14px;color: #0d64e8;font-weight: bolder">喇叭</el-row>
              <el-row style="text-align:center;font-size: 14px;color: #0d64e8;font-weight: bolder">灯光</el-row>
            </el-col>
            <el-col :span="3">
              <el-row style="text-align:center;font-size: 14px;color: #0d64e8;font-weight: bolder">电机</el-row>
              <el-row style="text-align:center;font-size: 14px;color: #0d64e8;font-weight: bolder">屏幕</el-row>
            </el-col>
          </el-row>
          <el-row style="margin-bottom: 15px">
            <el-col :span="3"
                    style="text-align:center;font-size: 18px;color: #0d64e8;font-weight: bolder;margin-top: -3px">
              原始数据
            </el-col>
            <el-col :span="3" style="text-align:center;font-size: 14px;color: #0d64e8;font-weight: bolder">
              Can
            </el-col>
            <el-col :span="3" style="text-align:center;font-size: 14px;color: #0d64e8;font-weight: bolder">
              TCP/IP
            </el-col>
            <el-col :span="3" style="text-align:center;font-size: 14px;color: #0d64e8;font-weight: bolder">
              I/O
            </el-col>
            <el-col :span="3" style="text-align:center;font-size: 14px;color: #0d64e8;font-weight: bolder">
              PLC
            </el-col>
            <el-col :span="3" style="text-align:center;font-size: 14px;color: #0d64e8;font-weight: bolder">
              Modbus
            </el-col>
            <el-col :span="3" style="text-align:center;font-size: 14px;color: #0d64e8;font-weight: bolder">
              RS232/485
            </el-col>
            <el-col :span="2" style="text-align:center;font-size: 14px;color: #0d64e8;font-weight: bolder">
              USB
            </el-col>
          </el-row>
        </el-col>
        <el-col :span="11" style="border: 2px dashed #0d64e8;margin-left: 1%;height: 179px">
          <el-row style="padding-top: 15px;padding-bottom: 15px">
            <el-col :span="9">
              &nbsp;
            </el-col>
            <el-col :span="3"
                    style="border: 2px solid #0d64e8;background-color: #0d64e8;border-top-left-radius: 15%;border-bottom-left-radius: 15%;
                    text-align:center;font-size: 18px;color: white;font-weight: bolder;padding-top: 10px;padding-bottom: 10px">
              控制
            </el-col>
            <el-col :span="3"
                    style="border: 2px solid #0d64e8;border-top-right-radius: 15%;border-bottom-right-radius: 15%;
                    text-align:center;font-size: 18px;color: #0d64e8;font-weight: bolder;padding-top: 10px;padding-bottom: 10px">
              输出
            </el-col>
            <el-col :span="9">
              &nbsp;
            </el-col>
          </el-row>
          <el-row
              style="padding-left: 10px;padding-right: 10px;padding-top: 15px;padding-bottom:30px;margin-bottom:0;margin-left: 20px">
            <el-col :span="2"
                    style="border: 2px solid #0d64e8;border-radius: 10%;background-color: #0d64e8;text-align:center;
                    font-size: 14px;color: white;font-weight: bolder;padding-top: 4px;padding-bottom: 4px">
              电机<br>控制
            </el-col>
            <el-col :span="3"
                    style="margin-left: 1%;border: 2px solid #0d64e8;border-radius: 10%;background-color: #0d64e8;
                    text-align:center;font-size: 14px;color: white;font-weight: bolder;padding-top: 14px;padding-bottom: 14px">
              气缸控制
            </el-col>
            <el-col :span="3"
                    style="margin-left: 1%;border: 2px solid #0d64e8;border-radius: 10%;background-color: #0d64e8;
                    text-align:center;font-size: 14px;color: white;font-weight: bolder;padding-top: 14px;padding-bottom: 14px">
              模拟量控制
            </el-col>
            <el-col :span="3"
                    style="margin-left: 1%;border: 2px solid #0d64e8;background-color: #0d64e8;border-top-left-radius: 15%;
                    border-bottom-left-radius: 15%;text-align:center;font-size: 14px;color: white;font-weight: bolder;padding-top: 14px;padding-bottom: 14px">
              I/O量控制
            </el-col>
            <el-col :span="3"
                    style="border: 2px solid #0d64e8;border-top-right-radius: 15%;border-bottom-right-radius: 15%;
                    text-align:center;font-size: 14px;color: #0d64e8;font-weight: bolder;padding-top: 14px;padding-bottom: 14px">
              屏幕显示
            </el-col>
            <el-col :span="3"
                    style="margin-left: 1%;border: 2px solid #0d64e8;border-radius: 10%;text-align:center;
                    font-size: 14px;color: #0d64e8;font-weight: bolder;padding-top: 14px;padding-bottom: 14px">
              网络输出
            </el-col>
            <el-col :span="3"
                    style="margin-left: 1%;border: 2px solid #0d64e8;border-radius: 10%;text-align:center;
                    font-size: 14px;color: #0d64e8;font-weight: bolder;padding-top: 14px;padding-bottom: 14px">
              多机协同
            </el-col>
            <el-col :span="2"
                    style="margin-left: 1%;border: 2px solid #0d64e8;border-radius: 10%;text-align:center;
                    font-size: 14px;color: #0d64e8;font-weight: bolder;padding-top: 4px;padding-bottom: 4px">
              云端<br>输出
            </el-col>
          </el-row>
        </el-col>

      </el-row>


      <!--    第二行 为什么做机器人操作系统  -->
      <el-footer class="sub_title">
        <p class="footer">为什么做机器人操作系统？</p>
      </el-footer>
      <el-row>
        <el-col id="row-two" :span="8">
          <p id="rt_text1">GomROS机器人操作系统</p>
          <p id="rt_text2">在经历了2018年以来的&quot;卡脖子&quot;风波之后，以工业软件、
            基础软件为代表的核心技术，自主研发自主拥有知识产权的需求更为强烈。</p>
          <p id="rt_text3">欢迎您加入我们的开发者队伍，我们一起打造国产基础软件系统。</p>
        </el-col>
        <el-col :span="6" style="margin-top: 2%">
          <img class="img-box row2_img" src="static/img/RobotOperateSystem/u779.png">
        </el-col>
        <el-col :span="6" style="margin-top: 2%">
          <img class="img-box row2_img" src="static/img/RobotOperateSystem/u780.png">
        </el-col>
      </el-row>

      <!--    第三行 机器人操作系统有哪些应用  -->
      <el-footer class="sub_title">
        <p class="footer">机器人操作系统有哪些应用？</p>
      </el-footer>
      <el-row id="row3">
        <el-col :span="11">
          <el-row id="row3_text">
            <p id="row3_text1">GomROS机器人操作系统</p>
            <p id="row3_text2">可用于多种行业、可用于多种类型机器人开发、可用于各类硬件设备驱动和控制。</p>
            <p id="row3_text3">GomROS可以帮助您快速完成机器人开发项目。</p>
          </el-row>
          <el-row :gutter="5" type="flex" style="margin-left: 2%">
            <el-col>
              <img class="img-box row3_img3" src="static/img/RobotOperateSystem/u800.gif">
            </el-col>
            <el-col>
              <img class="img-box row3_img3" src="static/img/RobotOperateSystem/u801.gif">
            </el-col>
            <el-col>
              <img class="img-box row3_img3" src="static/img/RobotOperateSystem/u802.gif">
            </el-col>
            <el-col>
              <img class="img-box row3_img3" src="static/img/RobotOperateSystem/u803.gif">
            </el-col>
          </el-row>
        </el-col>
        <el-col :span="11" style="margin-top: 2%">
          <el-row :gutter="20" type="flex" style="margin-left: 18%;margin-top: 10%;">
            <el-col>
              <img src="static/img/RobotOperateSystem/u785.png" class="row3_img1">
            </el-col>
            <el-col>
              <img src="static/img/RobotOperateSystem/u786.png" class="row3_img1">
            </el-col>
            <el-col>
              <img src="static/img/RobotOperateSystem/u787.png" class="row3_img1">
            </el-col>
            <el-col>
              <img src="static/img/RobotOperateSystem/u788.png" class="row3_img1">
            </el-col>
            <el-col>
              <img src="static/img/RobotOperateSystem/u789.png" class="row3_img1">
            </el-col>
          </el-row>
          <el-row :gutter="5" type="flex">
            <el-col>
              <img src="static/img/RobotOperateSystem/u790.jpg" class="row3_img2">
            </el-col>
            <el-col>
              <img src="static/img/RobotOperateSystem/u791.png" class="row3_img2">
            </el-col>
            <el-col>
              <img src="static/img/RobotOperateSystem/u792.png" class="row3_img2">
            </el-col>
            <el-col>
              <img src="static/img/RobotOperateSystem/u793.png" class="row3_img2">
            </el-col>
            <el-col>
              <img src="static/img/RobotOperateSystem/u794.png" class="row3_img2">
            </el-col>
            <el-col>
              <img src="static/img/RobotOperateSystem/u795.png" class="row3_img2">
            </el-col>
            <el-col>
              <img src="static/img/RobotOperateSystem/u796.jpg" class="row3_img2">
            </el-col>
            <el-col>
              <img src="static/img/RobotOperateSystem/u797.jpg" class="row3_img2">
            </el-col>
            <el-col>
              <img src="static/img/RobotOperateSystem/u798.png" class="row3_img2">
            </el-col>
            <el-col>
              <img src="static/img/RobotOperateSystem/u799.jpg" class="row3_img2">
            </el-col>
          </el-row>
        </el-col>
      </el-row>

      <!--    第四行  我们的应用案例 -->
      <el-footer class="sub_title">
        <p class="footer">我们的应用案例</p>
      </el-footer>
      <el-row style="padding-bottom: 0;padding-right: 0">
        <el-col :span="6" style="margin-left: 80px">
          <p id="row4_text1">GomROS机器人操作系统</p>
          <p id="row4_text2">我们的服务机器人和搬运机器人全部基于GomROS系统搭建。</p>
          <p id="row4_text3">参考我们的机器人开发项目</p>
        </el-col>
        <el-col :span="15" class="row4_right">
          <el-row :gutter="2" type="flex" id="row4_right_row1">
            <el-col :span="5" class="row4_sub1">软件系统</el-col>
            <el-row :gutter="2" type="flex" class="row4_border1">
              <el-col :span="8" style="margin-right:1%">
                <el-row style="text-align: center">
                  <img src="static/img/RobotOperateSystem/u831.png" class="row4_img1">
                </el-row>
                <el-row id="r4right_r1text1">
                  云平台
                </el-row>
              </el-col>
              <el-col :span="8" style="margin-right:1%">
                <el-row style="text-align: center">
                  <img src="static/img/RobotOperateSystem/u822.png" class="row4_img1">
                </el-row>
                <el-row id="r4right_r1text2">
                  集群调度系统
                </el-row>
              </el-col>
              <el-col :span="8">
                <el-row style="text-align: center">
                  <img src="static/img/RobotOperateSystem/u820.png" class="row4_img1">
                </el-row>
                <el-row id="r4right_r1text3">
                  控制软件系统
                </el-row>
              </el-col>
            </el-row>
          </el-row>
          <el-row :gutter="2" type="flex" id="row4_right_row2">
            <el-col :span="4" class="row4_sub2">产品应用</el-col>
            <el-row :span="10" class="row4_border2">
              <img src="static/img/RobotOperateSystem/u8090.png" class="row4_img2">
              <el-col :span="8" class="r4right_r2text1">
                工业AMR
              </el-col>
              <el-col :span="7" class="r4right_r2text2">
                公共服务AVR
              </el-col>
              <el-col :span="7" class="r4right_r2text3">
                复合应用AMB
              </el-col>
            </el-row>
          </el-row>
        </el-col>
      </el-row>
      <el-row :gutter="2" type="flex" style="height: 160px;padding-top: 0;padding-bottom: 20px;margin-right: 2%;">
        <el-col :span="5">&nbsp;</el-col>
        <el-col :span="5" class="row4_sub3" style="margin-left: 10%">
          硬件驱动/控制
        </el-col>
        <el-row :gutter="12" type="flex" class="row4_border3">
          <el-col :span="8">
            <el-row style="text-align: center">
              <img src="static/img/RobotOperateSystem/u814.png" class="row4_img3">
            </el-row>
            <el-row id="r4right_r3text1">
              激光雷达
            </el-row>
          </el-col>
          <el-col :span="8">
            <el-row style="text-align: center">
              <img src="static/img/RobotOperateSystem/u815.png" class="row4_img3">
            </el-row>
            <el-row id="r4right_r3text2">
              3D视觉传感器
            </el-row>
          </el-col>
          <el-col :span="8">
            <el-row style="text-align: center">
              <img src="static/img/RobotOperateSystem/u816.png" class="row4_img3">
            </el-row>
            <el-row id="r4right_r3text3">
              伺服电机
            </el-row>
          </el-col>
          <el-col :span="8">
            <el-row style="text-align: center">
              <img src="static/img/RobotOperateSystem/u817.png" class="row4_img3">
            </el-row>
            <el-row id="r4right_r3text4">
              工控机
            </el-row>
          </el-col>
          <el-col :span="8">
            <el-row style="text-align: center">
              <img src="static/img/RobotOperateSystem/u818.png" class="row4_img3">
            </el-row>
            <el-row id="r4right_r3text5">
              I/O系统
            </el-row>
          </el-col>
        </el-row>
        <!--          </el-col>-->
        <el-col :span="1">&nbsp;</el-col>
      </el-row>
      <!--      底部     -->
      <el-container id="bottom">
        <el-main id="bottom-main">
          <el-row :gutter="24" id="bottom-row">
            <el-col :span="13" id="bottom-text">
              欢迎咨询GomROS系统相关专家获取解决方案
            </el-col>
            <el-col :span="11" id="bottom-bt">
              <el-button id="bottom-button" @click="$router.push('/about')">
                联系我们
              </el-button>
            </el-col>
          </el-row>
        </el-main>
      </el-container>
    </div>
  </div>
</template>

<script>
</script>

<style scoped>

.el-row {
  padding: 2% 4%;
  /*animation: flipInX 1s;*/
}

.el-col h4 {
  font-size: 40px;
  color: #0d64e8;
  transition: 0.4s;
}

.el-col p {
  color: #484848;
  font-size: 15px;
  transition: 0.4s;
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-line-clamp: 6;
  overflow: hidden;
}

.el-col p:hover {
  color: #14679f;
}

#top-outline {
  width: 100%;
  padding: 0;
  height: 400px;
}

#top-bc {
  background-color: #36353b;
  height: 100%;
}

#company-logo {
  /*padding-top: 0px;*/
  /*padding-left: 0px;*/
  margin-right: 80px;
}

.cl-img {
  width: 240px;
  height: 240px;
}

#tc-text {
  margin-top: 5px;
  margin-left: 20px;
  text-shadow: 2px 2px 5px white;
}

.font_basic {
  font-size: 18px;
  color: #0D64E8;
  font-weight: bolder;
}

#top_explain {
  font-size: 28px;
  color: white;
  text-shadow: none;
  font-weight: bolder;
  margin-right: 10%;
}

#top-bcr {
  height: 100%;
  background-image: url(../../static/img/MobileRobot/u160.jpg);
  background-size: cover;
}

#top-footer {
  background-color: #0d64e8;
}

#tf-text {
  font-size: 32px;
  font-weight: bolder;
  color: white;
  margin-top: 10px;
  margin-bottom: 0;
  margin-left: 7%;
  height: 100px;
}

.img-box {
  text-align: center;
}

.background_white {
  background-color: white;
}

#ro-text1 {
  font-size: 32px;
  color: #0d64e8;
  font-weight: bolder;
}

#ro-text2 {
  font-size: 26px;
  color: #0d64e8;
  font-weight: bolder;
}

#ro-text3 {
  font-size: 32px;
  color: #0d64e8;
  font-weight: bolder;
}

#row-one {
  align-content: center;
  margin-left: 5%;
}

#ro_img1_text {
  width: 120px;
  background-color: #0d64e8;
  color: white;
  font-weight: bolder;
  font-size: 20px;
}

#ro_img2_text {
  width: 120px;
  background-color: #0d64e8;
  color: white;
  font-weight: bolder;
  font-size: 20px;
}

#ro_img3_text {
  width: 120px;
  background-color: #0d64e8;
  color: white;
  font-weight: bolder;
  font-size: 20px;
}

#ro_img4_text {
  width: 120px;
  background-color: #0d64e8;
  color: white;
  font-weight: bolder;
  font-size: 20px;
}

#ro_down {
  margin-left: 5%;
  width: 90%
}

.sub_title {
  background-color: #0d64e8;
  height: 80px
}

.footer {
  font-size: 32px;
  font-weight: bolder;
  color: white;
  margin-left: 3%;
  margin-top: 0;
  margin-bottom: 0;
  padding-top: 8px;

}

#row-two {
  margin-left: 3%;
  margin-right: 5%;
  width: 40%;
}

#rt_text1 {
  font-size: 32px;
  color: #0d64e8;
  font-weight: bolder;
}

#rt_text2 {
  font-size: 26px;
  color: #0d64e8;
  font-weight: bolder;
}

#rt_text3 {
  font-size: 32px;
  color: #0d64e8;
  font-weight: bolder;
}

.row2_img {
  width: 80%;
  height: 200px;
  margin-top: 8%;
}

#row3 {
  padding-top: 2px;
}

#row3_text {
  margin-left: 3%;
  width: 100%;
}

#row3_text1 {
  font-size: 32px;
  color: #0d64e8;
  font-weight: bolder;
}

#row3_text2 {
  font-size: 26px;
  color: #0d64e8;
  font-weight: bolder;
}

#row3_text3 {
  font-size: 26px;
  color: #0d64e8;
  font-weight: bolder;
  margin-bottom: 0;
}

.row3_img1 {
  height: 100px;
  width: 100px;
}

.row3_img2 {
  height: 80px;
  width: 80px;
}

.row3_img3 {
  width: 95%;
  height: 100%;
}

#row4_text1 {
  font-size: 32px;
  color: #0d64e8;
  font-weight: bolder;
}

#row4_text2 {
  font-size: 26px;
  color: #0d64e8;
  font-weight: bolder;
}

#row4_text3 {
  font-size: 32px;
  color: #0d64e8;
  font-weight: bolder;
  margin-top: 10%;
}

.row4_right {
  align-content: center;
}

.row4_sub1 {
  text-align: center;
  font-size: 32px;
  font-weight: bolder;
  color: #0d64e8;
  margin-top: 5%;
  margin-right: 1px;
}

#row4_right_row1 {
  width: 100%;
  height: 200px;
  padding-left: 20%;
  padding-right: 10px;
  padding-bottom: 0;
}

.row4_border1 {
  text-align: center;
  border: 2px dashed dodgerblue;
  width: 100%;
  height: 150px;
  padding-top: 0;
  padding-left: 10px;
  padding-right: 10px;
}

.row4_img1 {
  width: 190px;
  height: 110px;
}

#r4right_r1text1 {
  width: 100%;
  font-size: 15px;
  font-weight: bolder;
  color: #0d64e8;
  margin-top: 0;
  margin-bottom: 0;
  padding-top: 0;
  padding-bottom: 0;
  text-align: center;
}

#r4right_r1text2 {
  width: 100%;
  font-size: 15px;
  font-weight: bolder;
  color: #0d64e8;
  margin-top: 0;
  margin-bottom: 0;
  padding-top: 0;
  padding-bottom: 0;
  text-align: center;
}

#r4right_r1text3 {
  width: 100%;
  font-size: 15px;
  font-weight: bolder;
  color: #0d64e8;
  margin-top: 0;
  margin-bottom: 0;
  padding-top: 0;
  padding-bottom: 0;
  text-align: center;
}

.row4_sub2 {
  text-align: center;
  font-size: 32px;
  font-weight: bolder;
  color: #0d64e8;
  margin-top: 4%;
  margin-right: 5px;
}

#row4_right_row2 {
  width: 100%;
  height: 160px;
  padding-right: 10px;
  padding-left: 10%;
  padding-top: 0;
}


.row4_border2 {
  text-align: center;
  border: 2px dashed dodgerblue;
  width: 85%;
  padding: 0;
}

.row4_img2 {
  height: 80%;
  width: 90%;
  padding: 1%;
}

.r4right_r2text1 {
  font-size: 15px;
  font-weight: bolder;
  margin-left: 2%;
  margin-right: 3%;
  color: #0d64e8;
}

.r4right_r2text2 {
  font-size: 15px;
  font-weight: bolder;
  margin-right: 2%;
  color: #0d64e8;
}

.r4right_r2text3 {
  font-size: 15px;
  font-weight: bolder;
  color: #0d64e8;

}

.row4_sub3 {
  text-align: center;
  font-size: 32px;
  font-weight: bolder;
  color: #0d64e8;
  margin-top: 2%;
  margin-right: 0px;
}

.row4_border3 {
  text-align: center;
  border: 2px dashed dodgerblue;
  width: 80%;
  height: 115px;
  padding: 0;
}

.row4_img3 {
  width: 60%;
  height: 80px;
  padding-top: 2px;
}

#r4right_r3text1 {
  width: 100%;
  font-size: 15px;
  font-weight: bolder;
  color: #0d64e8;
  margin-top: 0;
  margin-bottom: 0;
  padding-top: 0;
  padding-bottom: 0;
  text-align: center;
}

#r4right_r3text2 {
  width: 100%;
  font-size: 15px;
  font-weight: bolder;
  color: #0d64e8;
  margin-top: 0;
  margin-bottom: 0;
  padding-top: 0;
  padding-bottom: 0;
  text-align: center;
}

#r4right_r3text3 {
  width: 100%;
  font-size: 15px;
  font-weight: bolder;
  color: #0d64e8;
  margin-top: 0;
  margin-bottom: 0;
  padding-top: 0;
  padding-bottom: 0;
  text-align: center;
}

#r4right_r3text4 {
  width: 100%;
  font-size: 15px;
  font-weight: bolder;
  color: #0d64e8;
  margin-top: 0;
  margin-bottom: 0;
  padding-top: 0;
  padding-bottom: 0;
  text-align: center;
}

#r4right_r3text5 {
  width: 100%;
  font-size: 15px;
  font-weight: bolder;
  color: #0d64e8;
  margin-top: 0;
  margin-bottom: 0;
  padding-top: 0;
  padding-bottom: 0;
  text-align: center;
}

#bottom {
  width: 100%;
}

#bottom-main {
  background: #0d64e8;
  font-size: 30px;
}

#bottom-row {
  padding-top: 0;
  padding-bottom: 0;
}

#bottom-text {
  color: white;
  text-align: left;
  font-size: 35px;
  font-weight: bolder;
  padding-left: 5%;
}

#bottom-bt {
  text-align: right;
  padding-right: 1%;
}

#bottom-button {
  font-size: 30px;
  background-color: #0d64e8;
  border-color: white;
  color: white;
}

</style>
