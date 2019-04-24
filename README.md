# Udacity_robotics_term2_p2_where Am I
### Abstract
Monte-Carlo based localization is a widely use algorithm in robot application. The main application in robotics is called
particle filter. Particle filter is a kind of filter algorithm which is totally different with filter like KF, EKF, UKF family. Particle filer doesn’t
use moment of noise like mean value and variance value to filtering the noise. Particle filter use many particles to approximate many
kinds of noise distributions. So particle filter can extract any noise distribution and filtering any noise distribution with enough particles.
But as the quantity of particles grows, the more computation power it uses. So it is a trade off of computation efficiency and precision of
estimation. In this paper, a ROS package which is named ’AMCL’ with adaptive particle filter is used to localize

### video link :
* udacity bot: https://www.youtube.com/watch?v=BdYfmZvmWkM
* truck bot : https://www.youtube.com/watch?v=7WudvpSh_6s
![myrobot initialization](https://github.com/Fred159/Udacity_robotics_term2_p2_where-Am-I/blob/master/figure/Mingbot/ming_rviz.png)
