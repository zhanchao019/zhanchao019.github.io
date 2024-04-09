---
layout: default
title: demopage 
---

<div class="post">
    <style>
    img {
        width: auto;
        height: auto;
        max-width: 80%;
        max-height: 100%;
        display: block;
        margin: auto;
    }
    video {
        width: auto;
        height: auto;
        max-width: 100%;
        max-height: 100%;
        display: block;
        margin: auto;
    }
    </style>
	<h2 class="pageTitle">Video2Video Genereation Demos</h2>
	<p></p>
	<table border="0"> <!-- 表格边框设置为1 -->
    <tr> <!-- 表格的一行 -->
        <th style="width: 512px;">Image</th> <!-- 表头单元格 -->
        <th style="width: 512px;">Video</th> <!-- 表头单元格 -->
    </tr>
    </table>
		<table border="0"> <!-- 表格边框设置为1 -->
    <tr>
        <td>
            <img src="/assets/images/cyber_girl.png" width="512" height="900" alt="Image 3">
        </td>
        <td>
            <img src="/assets/images/spark_girl.png" width="512" height="900" alt="Image 3">
        </td>
    </tr>
</table>
    <video src="/assets/demo_videos/video1_plus.mp4"  width="1000" height="900" controls>
    </video>
	<h2 class="pageTitle">Long Video Genereation</h2>
	<p></p>
	<table border="0"> <!-- 表格边框设置为1 -->
    <tr> <!-- 表格的一行 -->
        <th style="width: 200px;">Source Video</th> <!-- 表头单元格 -->
        <th style="width: 800px;">Output Video</th> <!-- 表头单元格 -->
    </tr>
    </table>
		<table border="0"> <!-- 表格边框设置为1 -->
    <tr>
        <td>
            <video src="/assets/demo_videos/bath_song_lite.mp4"  width="200" height="900" controls></video>
        </td>
        <td>
            <video src="/assets/demo_videos/bath_lite.mp4"  width="800" height="900" controls></video>
        </td>
    </tr>
    <tr>
        <td>
            <video src="/assets/demo_videos/dance1.mp4"  width="200" height="900" controls></video>
        </td>
        <td>
            <video src="/assets/demo_videos/video1.mp4"  width="800" height="900" controls></video>
        </td>
    </tr>
</table>
</div>