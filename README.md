# arm版本

主要看最外面那层Dockerfile的动作，分别进子目录打包出镜像，再用打包好的步骤镜像生成最终镜像，最后跑docker-compose.yml   记得里面的mongo改成arm版本的，例如mongo:4.2.16-rc0-bionic