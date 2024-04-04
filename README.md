<div align="center">
	<h1>Navigation-Book：导航定位书籍讲义</h1>
    <h4>分享一些导航算法学习过程中对我起较大帮助的书籍、讲义、PPT</h4>
    <img alt="Static Badge" src="https://img.shields.io/badge/QQ-1482275402-red">
    <img alt="Static Badge" src="https://img.shields.io/badge/%E5%BE%AE%E4%BF%A1-lizhengxiao99-green">
    <img alt="Static Badge" src="https://img.shields.io/badge/Email-dauger%40126.com-brown">
    <a href="https://blog.csdn.net/daoge2666/"><img src="https://img.shields.io/badge/CSDN-论坛-c32136" /></a>
    <a href="https://www.zhihu.com/people/dao-ge-92-60/"><img src="https://img.shields.io/badge/Zhihu-知乎-blue" /></a>
    <img src="https://komarev.com/ghpvc/?username=LiZhengXiao99&label=Views&color=0e75b6&style=flat" alt="访问量统计" />
    <p>
        <img src="https://pic-bed-1316053657.cos.ap-nanjing.myqcloud.com/img/662bf58e5529e6a138945e9ffc90893e.png" alt="662bf58e5529e6a138945e9ffc90893e" width="400" />
    </p>
</div>

---

<table align="center">
    <tr align="center">
    	<th width="150">封面</th>
    	<th>简介</th>
    </tr>
    <tr>
    	<td>
            <img width="180" src="https://pic-bed-1316053657.cos.ap-nanjing.myqcloud.com/img/image-20240331145552445.png" alt="image-20240331145552445" style="zoom:;" />
        </td>
    	<td>
            <p align="center">
                <strong>《GPS原理与接收机设计》谢刚</strong>
            </p>
			<p>&nbsp;&nbsp;&nbsp;&nbsp;我最推荐的卫星导航入门参考书，全面且系统地介绍了GNSS的原理。从信号体制到接收机信号处理，从观测值误差分析到各种定位技术，再到航位推算、组合导航和地图匹配等，无一不包。这本书能让你深入透彻地理解GNSS的工作原理，为后续的进阶学习打下坚实的基础。</p>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;对于从事GNSS数据处理的朋友，我强烈推荐你们学习基带算法。只依赖接收机输出的伪距、载波、多普勒和信噪比等数据进行定位，还是太浅了；深入了解接收机内部的原理，包括卫星信号的结构、发射方式、传播过程，以及接收机的天线信号接收、射频前端处理、基带数字信号处理等全流程，能够让你对数据处理算法有更深刻的理解；而且许多GNSS的岗位不仅要求掌握定位技术，还要求对基带算法有所了解。</p>
        	<p align="center" > 👉👉👉&nbsp;  <a href='' target='_blank'>点击跳转</a> &nbsp;👈👈👈</p>
        </td>
    </tr>
    </tr>
        <tr>
        <td>
            <img width="180" src="https://pic-bed-1316053657.cos.ap-nanjing.myqcloud.com/img/image-20240331152342461.png" alt="image-20240331152342461" />
        </td>
        <td>
             <p align="center">
                <strong>《软件定义的GPS和伽利略接收机》</strong>
            </p>
            <p>
                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;薄薄的一小本，一百多面，我主要是推荐配套的开源程序SoftGNSS，MATLAB 编写，实现了一套最简单的 GNSS 软件接收机功；输入经过天线接收，射频前端滤波下变频后的数字中频信号文件，进行 GPS L1 C/A 码的捕获跟踪，生成伪距观测值，解译导航电文，最小二乘定位解算；代码量很小也很简单，适合作为 GNSS 基带数字信号处理的入门阅读程序。
            </p>
            <p align="center" > 👉👉👉&nbsp;  <a href='' target='_blank'>点击跳转</a> &nbsp;👈👈👈</p>
        </td>
    </tr>
    </tr>
        <tr>
        <td>
            <img width="180" src="https://pic-bed-1316053657.cos.ap-nanjing.myqcloud.com/img/image-20240331152305330.png" alt="image-20240331152305330" />
        </td>
        <td>
            <p align="center">
                <strong>《北斗GPS双模软件接收机》鲁郁</strong>
            </p>
            <p>
                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;主要是推荐书附带的程序，MATLAB 编写 GPS-L1/BDS-B1 软件接收机，学一学北斗信号处理算法，NH码处理啥的；程序运行相当耗时，70s 的数据要算几个小时。书写的有些部分写的比谢刚的《GPS原理与接收机设计》要细致深入，代码的有些部分处理的比SoftGNSS细致，可以结合着一块看。
            </p>
            <p align="center" > 👉👉👉&nbsp;  <a href='' target='_blank'>点击跳转</a> &nbsp;👈👈👈</p>
        </td>
    </tr>
    <tr>
        <td>
            <img width="180" src="https://pic-bed-1316053657.cos.ap-nanjing.myqcloud.com/img/image-20240331151907738.png" alt="image-20240331151907738" />
        </td>
        <td>
            <p align="center">
                <strong>《GPS测量与数据处理》李征航</strong>
            </p>
            <p>
                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;市面上有不少 GPS 数据处理算法的书，这本应该是看的人最多的，很多论文的参考文献列表里都有它，讲的很全面，很细致，可以准备一本在手头放着，有忘了的基础算法查一查；建议结合着 B 站赵乐文老师的《多模GNSS定位与应用介绍》课来看，赵老师的视频补充了很多的工程知识和多系统算法。
            </p>
            <p>
                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;当然，初学者光靠书是没法学明白 GPS 算法的，把整本书看完了，你可能还是捋不清该如何从伪距/载波/多普勒和星历，一步步算出 SPP/RTK/PPP 解；对算法有一些了解之后，就应该找一套开源程序深入学习，无论是科研还是工程实践，都可以在开源程序的基础上拓展，从而节省大量基础工作的时间和精力。
            </p>
            <p>
                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;至于其它的 GNSS 数据处理书，我都不推荐看，入了门之后就该看论文，先看综述，再看硕博学位论文，之后可以顺着引用的文献继续看；看综述，帮你快速了解所处领域的研究进展；看硕博论文，补充一些书上没讲到的算法和知识点；不推荐初学者看英文原著，英文书写的也不能比中文的强多少，但是英语带来的学习障碍可不小。
            </p>
            <p align="center" > 👉👉👉&nbsp;  <a href='' target='_blank'>点击跳转</a> &nbsp;👈👈👈</p>
        </td>
    </tr>
    <tr>
        <td>
            <img width="180" src="https://pic-bed-1316053657.cos.ap-nanjing.myqcloud.com/img/image-20240331150756809.png" alt="image-20240331150756809" />
        </td>
        <td>
            <p align="center">
                <strong>《GNSS与惯性及多传感器组合导航系统原理》Groves</strong>
            </p>
            <p>
                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;我最推荐的惯导和组合导航入门参考书，写的通俗易懂，比其它的惯导书易读的多；七百多面，把组合导航的方方面面都介绍到了（除了初始对准）。惯导入门建议直接学捷联惯导（不建议学平台惯导，现在很少用到），把几种姿态旋转、几种坐标系理解了之后，对着公式看代码。
            </p>
            <p align="center" > 👉👉👉&nbsp;  <a href='' target='_blank'>点击跳转</a> &nbsp;👈👈👈</p>
        </td>
    </tr>
    <tr>
        <td>
            <img width="180" src="https://pic-bed-1316053657.cos.ap-nanjing.myqcloud.com/img/image-20240331150652642.png" alt="image-20240331150652642" />
        </td>
        <td>
			<p align="center">
                <strong>《捷联惯导算法与组合导航讲义》严恭敏</strong>
            </p>
            <p>
                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;严老师把捷联惯导、组合导航的算法讲的很透彻，不过整本书都是公式推导，学起来相当有难度；前三章介绍常用姿态、坐标系，地球相关参数计算，第四章介绍捷联惯导递推、误差传播，五六章介绍参数估计、各种滤波，第七章介绍松组合、初始对准，第八章讲仿真。B 站有上配套的视频课《卡尔曼滤波与组合导航》，严老师开源了配套的 MATLAB 捷联惯导工具箱 PSINS，都是入门捷联惯导、组合导航不错的资料。
            </p>
            <p align="center" > 👉👉👉&nbsp;  <a href='' target='_blank'>点击跳转</a> &nbsp;👈👈👈</p>
        </td>
    </tr>
	</tr>
        <tr>
        <td>
            <img width="180" src="https://pic-bed-1316053657.cos.ap-nanjing.myqcloud.com/img/image-20240331152721060.png" alt="image-20240331152721060" />
        </td>
        <td>
            <p align="center">
                <strong>《视觉SLAM十四讲》高翔</strong>
            </p>
            <p>
                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;SLAM入门首选参考书，系统介绍了视觉SLAM所需的基本知识与核心算法，内容全面、结构清晰、理论与实践相结合。既包含数学理论基础，如三维空间的刚体运动、非线性优化，又涵盖计算机视觉的算法实现，如多视图几何、相机标定、图优化、卡尔曼滤波等。而且作者提供了大量的实例代码供读者学习研究，有助于读者更深入地掌握SLAM技术的实现细节。网上有很多相关的读数笔记，相关的网课，可以作为入门学习的参考。
            </p>
            <p align="center" > 👉👉👉&nbsp;  <a href='' target='_blank'>点击跳转</a> &nbsp;👈👈👈</p>
        </td>
    </tr>
	</tr>
        <tr>
        <td>
            <img width="180" src="https://pic-bed-1316053657.cos.ap-nanjing.myqcloud.com/img/image-20240331152834041.png" alt="image-20240331152834041" />
        </td>
        <td>
            <p align="center">
                <strong>《视觉惯性SLAM》程小六</strong>
            </p>
            <p>
                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;计算机视觉Life程小六写的ORB-SLAM3的源码解析，质量比大部分的博客讲义高的多，学完《视觉SLAM十四讲》就该继续学常用的SLAM框架，结合着代码深入学算法，基于ORB特征点的ORB-SLAM3是一个不错的选择，支持单目/双目/RGB-D、惯性紧组合、回环检测、重定位，在开源数据集上有不错的效果，缺点是计算量大、代码BUG多、对外参标定要求高。在六哥的知识星球《小六的机器人AI圈》中有读书挑战赛活动，感兴趣可以去看看。
            </p>
            <p align="center" > 👉👉👉&nbsp;  <a href='' target='_blank'>点击跳转</a> &nbsp;👈👈👈</p>
        </td>
    </tr>
	</tr>
        <tr>
        <td>
            <img width="180" src="https://pic-bed-1316053657.cos.ap-nanjing.myqcloud.com/img/image-20240401082145458.png" alt="image-20240401082145458" />
        </td>
        <td>
            <p align="center">
                <strong>《自动驾驶中的SLAM技术》高翔</strong>
            </p>
            <p>
                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;既《视觉SLAM十四讲》后高翔的又一力作，系统的介绍激光惯性SLAM理论，采用 C++17 标准编写例程，全书分三部分：
            </p>
            <ul>
    			<li><strong>基础数学知识：</strong>基础几何学、运动学知识，参数估计回顾，IMU预积分</li>
    			<li><strong>激光雷达的定位与建图：</strong>基础点云算法、2D-SLAM、3D-SLAM、激光惯性松组合里程计</li>
    			<li><strong>应用实例：</strong>Lins、离线点云地图构建、已有点云地图中定位、实时定位</li>
				</ul>
            <p align="center" > 👉👉👉&nbsp;  <a href='' target='_blank'>点击跳转</a> &nbsp;👈👈👈</p>
        </td>
    </tr>
    <tr>
        <td>
            <img width="180" src="https://pic-bed-1316053657.cos.ap-nanjing.myqcloud.com/img/image-20240331152222633.png" alt="image-20240331152222633" />
        </td>
        <td>
            <p align="center">
                <strong>《概率机器人》塞巴斯蒂安·特龙</strong>
            </p>
            <p>
                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;相当好的机器人导航入门参考书，包括了参数估计、定位、地图构建、规划与控制四大部分；每章的最后都提供了练习题和动手实践的项目；对于每种算法，均提供了：①伪码示例；②完整的数学推导；③实验结果；④算法优缺点的详细讨论。
            </p>
            <p>
                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;既使你不做机器人导航、不做SLAM，也推荐你看看它的前四章，参数估计部分，相信能让你对最小二乘、卡尔曼滤波有更深一层次的认识。
            </p>
            <p align="center" > 👉👉👉&nbsp;  <a href='' target='_blank'>点击跳转</a> &nbsp;👈👈👈</p>
        </td>
    </tr>
    <tr>
        <td>
            <img width="180" src="https://pic-bed-1316053657.cos.ap-nanjing.myqcloud.com/img/image-20240331151755099.png" alt="image-20240331151755099" />
        </td>
        <td>
            <p align="center">
                <strong>《自适应动态导航定位》杨元喜</strong>
            </p>
            <p>
                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;首先分析了函数模型误差补偿和随机模型误差补偿法；讨论了Kalman滤波的残差向量、新息向量及状态预报值残差向量的解析关系及协方差矩阵之间的关系；分析了基于新息向量、残差向量和状态预报值残差向量的自适应协方差估计存在的问题；对抗差滤波、Sage自适应滤波进行了综合比较与分析。创建了一套全新的动态自适应抗差滤波理论体系，研究了相应解的性质。构造了三段函数、两段函数和指数函数三种动态自适应因子；讨论了Sage滤波与自适应滤波组合的导航解算方法，基于方差分量估计的自适应滤波理论。构造了最优自适应滤波理论。建立了卫星轨道的自适应定轨理论与方法，提出了一种综合Sage滤波和自适应抗差滤波的新的轨道计算方法。最后对组合导航理论进行了探讨。
            </p>
            <p align="center" > 👉👉👉&nbsp;  <a href='' target='_blank'>点击跳转</a> &nbsp;👈👈👈</p>
        </td>
    </tr>
    </tr>
        <tr>
        <td>
            <img width="180" src="https://pic-bed-1316053657.cos.ap-nanjing.myqcloud.com/img/image-20240331193252920.png" alt="image-20240331193252920" />
        </td>
        <td>
            <p align="center">
                <strong>《C++Premier》</strong>
            </p>
            <p>
                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;直译过来叫“C++入门”，但不适合完全零基础看，适合初学者上过了C语言或者C++课，有了一点点基础之后看，难度比其它的 C++ 入门书籍、教材稍大，写的很详细，不光讲语法，还会讲一些代码设计经验以及一些避坑指南，文笔幽默风趣让人心情愉悦；可以放一本在手边，语法生疏了，查一下；它还有个简略的版本：《C++ Premier Plus》，也是C++入门不错的参考书。
            </p>
			<p align="center" > 👉👉👉&nbsp;  <a href='' target='_blank'>点击跳转</a> &nbsp;👈👈👈</p>
        </td>
    </tr>
    </tr>
        <tr>
        <td>
            <img width="180" src="https://pic-bed-1316053657.cos.ap-nanjing.myqcloud.com/img/image-20240331152422181.png" alt="image-20240331152422181" />
        </td>
        <td>
            <p align="center">
                <strong>《EffectiveC++》</strong>
            </p>
            <p>
                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;以条款的形式列举了55条C++语法的使用建议，帮助我们提高代码质量、性能、可读性、可拓展性，让我们对 C++ 编程的理解更上一层楼；使用的 C++ 版本比较老，很多内容不适用于现代 C++，看完之后可以再看看类似的《Modern Effective C++》、《Effective STL》。
            </p>
            <p align="center" > 👉👉👉&nbsp;  <a href='' target='_blank'>点击跳转</a> &nbsp;👈👈👈</p>
        </td>
    </tr>
	</tr>
        <tr>
        <td>
            <img width="180" src="https://pic-bed-1316053657.cos.ap-nanjing.myqcloud.com/img/image-20240401082527986.png" alt="image-20240401082527986" />
        </td>
        <td>
            <p align="center">
                <strong>《C++20高级编程》</strong>
            </p>
            <p>
                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;全面、详实的介绍了C++的方方面面，还有案例讲解，非常适合现代C++入门学者；C++ Primer没涵盖新的语法特性（仅到C++11），而且将来也大概率不会涵盖了，因为作者已经去世了；市面上其他介绍C++20的书，大多都只介绍C++的新特性，是给那些已经掌握了C++的读者读的（用来了解新特性），不适合初学者。
            </p>
            <p align="center" > 👉👉👉&nbsp;  <a href='' target='_blank'>点击跳转</a> &nbsp;👈👈👈</p>
        </td>
    </tr>
	<tr>
        <td>
            <img width="180" src="https://pic-bed-1316053657.cos.ap-nanjing.myqcloud.com/img/image-20240331150921116.png" alt="image-20240331150921116" />
        </td>
        <td>
            <p align="center">
                <strong>《测绘程序设计》李英冰</strong>
            </p>
            <p>
                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;测绘程序设计比赛的参考书，每一节介绍一种测绘相关的算法（大地主题正反算、空间前方交会、伪距单点定位等）提供了配套的示例程序（C#为主，一大半程序都有BUG），测绘类院校学生学完了编程语法，就可以从这里找程序练练手；建议初学者先认准一套程序学，先把例程跑通、读懂，然后照着例程敲两遍，再脱离例程试着从头自己写。数据处理算法，无外乎就是三部分：读取数据、数值计算、输出结果，提供练习这里的程序都可以学到；把这书上几百行的代码学明白、写明白了，你再去看正儿八经的上万行的开源程序就容易多了。
            </p>
        	<p align="center" > 👉👉👉&nbsp;  <a href='' target='_blank'>点击下载</a> &nbsp;👈👈👈</p>
		</td>
    </tr>
    <tr>
        <td>
            <img width="180" src="https://pic-bed-1316053657.cos.ap-nanjing.myqcloud.com/img/image-20240331153002713.png" alt="image-20240331153002713" />
        </td>
        <td>
            <p align="center">
                <strong>《大话数据结构》程杰</strong>
            </p>
            <p>
                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;数据结构通常被认为是计算机科班学生最重要的课，面试要考算法题，找工作前要刷LeetCode；对我们非科班写算法的程序员也同样重要，懂点数据结构和算法，你才能写出更高效的程序，你才能学明白STL，而且我们找算法相关的工作也可能要考算法题的；咱不一定要像科班学生掌握那么熟练，能理解常用的数据结构、算法就行，并不需要都会实现。
            </p>
            <p>
                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;咱们学数据结构和算法推荐看《大话数据结构》，它用生动有趣的对话、直观的图示，将复杂的数据结构概念变得简单易懂，让读者能够轻松掌握数据结构的基本原理和应用，进而提升编程能力和算法思维，它不像正儿八经的课本那么枯燥，对咱们非科班的程序员相当的友好。
            </p>
            <p align="center" > 👉👉👉&nbsp;  <a href='' target='_blank'>点击下载</a> &nbsp;👈👈👈</p>
        </td>
    </tr>
</table>

