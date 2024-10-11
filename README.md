# maxView
maxView系统远程代码执行
<img width="471" alt="985c6c9eef6204ace44cb35ae3db4de" src="https://github.com/user-attachments/assets/a11484c6-09fb-434d-8300-8bb624bbed66">
# 使用线程池并发执行检查漏洞
    with concurrent.futures.ThreadPoolExecutor(max_workers=20) as executor:
        executor.map(check_vulnerability, targets)
自己创建url.txt，文档中包含测试的网站
