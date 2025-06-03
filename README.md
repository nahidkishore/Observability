# Observability-Project-
![Black and White Groovy Keep Going Desktop Wallpaper](https://github.com/user-attachments/assets/0e83b5df-de58-4b6e-a6b0-d1fc7bc26368)





# Docker image build process:

```bash
docker build -t nahid0002/service-metrics-a:v1 .
docker build -t nahid0002/service-metrics-b:v1 .
docker images
docker login
docker push nahid0002/service-metrics-a:v1
docker push nahid0002/service-metrics-b:v1
```