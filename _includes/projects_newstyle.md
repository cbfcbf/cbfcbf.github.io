<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>项目展示</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #f8f9fa;
            color: #333;
            line-height: 1.6;
        }
        .projects-container {
            max-width: 1000px;
            margin: 0 auto;
            padding: 20px;
        }
        .section-title {
            text-align: center;
            margin-bottom: 40px;
            color: #2c3e50;
            font-weight: 600;
            position: relative;
        }
        .section-title:after {
            content: '';
            display: block;
            width: 80px;
            height: 4px;
            background: linear-gradient(90deg, #3498db, #2c3e50);
            margin: 10px auto 0;
            border-radius: 2px;
        }
        .project-item {
            background: white;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
            margin-bottom: 30px;
            overflow: hidden;
            transition: transform 0.3s, box-shadow 0.3s;
        }
        .project-item:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.1);
        }
        .project-content {
            padding: 25px;
        }
        .project-title {
            font-size: 1.4rem;
            font-weight: 600;
            margin-bottom: 10px;
            color: #2c3e50;
        }
        .project-title a {
            text-decoration: none;
            color: inherit;
            transition: color 0.3s;
        }
        .project-title a:hover {
            color: #3498db;
        }
        .project-authors {
            color: #7f8c8d;
            font-style: italic;
            margin-bottom: 10px;
        }
        .project-conference {
            color: #3498db;
            font-weight: 500;
            margin-bottom: 15px;
        }
        .project-image {
            width: 100%;
            height: 300px;
            object-fit: cover;
            border-bottom: 1px solid #eee;
        }
        .project-badge {
            position: absolute;
            top: 15px;
            right: 15px;
            background: #3498db;
            color: white;
            padding: 5px 12px;
            border-radius: 20px;
            font-size: 0.8rem;
            font-weight: 500;
        }
        .project-links {
            margin-top: 20px;
        }
        .btn-project {
            background-color: #f8f9fa;
            border: 1px solid #dee2e6;
            color: #495057;
            margin-right: 8px;
            margin-bottom: 8px;
            border-radius: 20px;
            padding: 6px 15px;
            font-size: 0.85rem;
            transition: all 0.3s;
        }
        .btn-project:hover {
            background-color: #3498db;
            color: white;
            border-color: #3498db;
        }
        .project-notes {
            color: #e74c3c;
            font-weight: 500;
            margin-top: 10px;
        }
        .image-container {
            position: relative;
        }
    </style>
</head>
<body>
    <div class="projects-container">
        <h2 class="section-title">项目展示</h2>
        
        <div class="project-list">
            <!-- 项目1 -->
            <div class="project-item">
                <div class="image-container">
                    <img src="https://images.unsplash.com/photo-1555949963-aa79dcee981c?ixlib=rb-1.2.1&auto=format&fit=crop&w=1000&q=80" alt="项目图片" class="project-image">
                    <span class="project-badge">CVPR 2023</span>
                </div>
                <div class="project-content">
                    <h3 class="project-title"><a href="#">基于深度学习的图像语义分割系统</a></h3>
                    <div class="project-authors">张三，李四，王五</div>
                    <div class="project-conference">IEEE Conference on Computer Vision and Pattern Recognition (CVPR)</div>
                    <p class="project-description">本项目提出了一种新的语义分割框架，结合了注意力机制和多尺度特征融合，在多个公开数据集上取得了领先的性能。</p>
                    <div class="project-links">
                        <a href="#" class="btn btn-project">PDF</a>
                        <a href="#" class="btn btn-project">代码</a>
                        <a href="#" class="btn btn-project">项目主页</a>
                        <a href="#" class="btn btn-project">BibTex</a>
                    </div>
                    <div class="project-notes">亮点：在Cityscapes数据集上达到85.3% mIoU</div>
                </div>
            </div>
            
            <!-- 项目2 -->
            <div class="project-item">
                <div class="image-container">
                    <img src="https://images.unsplash.com/photo-1551288049-bebda4e38f71?ixlib=rb-1.2.1&auto=format&fit=crop&w=1000&q=80" alt="项目图片" class="project-image">
                    <span class="project-badge">NeurIPS 2022</span>
                </div>
                <div class="project-content">
                    <h3 class="project-title"><a href="#">自适应图神经网络在推荐系统中的应用</a></h3>
                    <div class="project-authors">赵六，钱七，孙八</div>
                    <div class="project-conference">Neural Information Processing Systems (NeurIPS)</div>
                    <p class="project-description">我们提出了一种自适应图神经网络架构，能够动态调整节点间的关系权重，在多个推荐系统基准测试中显著提升了推荐准确率。</p>
                    <div class="project-links">
                        <a href="#" class="btn btn-project">PDF</a>
                        <a href="#" class="btn btn-project">代码</a>
                        <a href="#" class="btn btn-project">项目主页</a>
                        <a href="#" class="btn btn-project">BibTex</a>
                    </div>
                </div>
            </div>
            
            <!-- 项目3 -->
            <div class="project-item">
                <div class="image-container">
                    <img src="https://images.unsplash.com/photo-1555255707-c07966088b7b?ixlib=rb-1.2.1&auto=format&fit=crop&w=1000&q=80" alt="项目图片" class="project-image">
                    <span class="project-badge">ICML 2023</span>
                </div>
                <div class="project-content">
                    <h3 class="project-title"><a href="#">基于元学习的少样本分类方法</a></h3>
                    <div class="project-authors">周九，吴十，郑十一</div>
                    <div class="project-conference">International Conference on Machine Learning (ICML)</div>
                    <p class="project-description">本研究探索了元学习在少样本分类任务中的应用，提出了一种新的元学习框架，能够在少量样本情况下快速适应新任务。</p>
                    <div class="project-links">
                        <a href="#" class="btn btn-project">PDF</a>
                        <a href="#" class="btn btn-project">代码</a>
                        <a href="#" class="btn btn-project">项目主页</a>
                    </div>
                    <div class="project-notes">在Mini-ImageNet 5-way 1-shot任务中达到72.5%准确率</div>
                </div>
            </div>
        </div>
    </div>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>