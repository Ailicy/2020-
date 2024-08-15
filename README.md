大创实物视频演示

mkdir my-video-repo    //创建git仓库
cd my-video-repo        //
git init                //初始化


git clone https://github.com/your-username/your-repository.git    //克隆github仓库到本地仓库
cd your-repository   //cd到本地仓库

cp /path/to/your/大创结题.mp4 .     //将大创结题视频复制到本地仓库目录

大创视频为198M，超出限制


git lfs track "大创结题.mp4"       //

git add .gitattributes
git commit -m "Track video files using Git LFS"   //

git add path/to/大创结题.mp4      //添加大文件到git
git commit -m "Add large video file"   //提交

git push origin main     //推送到github


