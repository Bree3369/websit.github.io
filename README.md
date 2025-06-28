<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>求职信 - 张三</title>
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Font Awesome -->
    <link href="https://cdn.jsdelivr.net/npm/font-awesome@4.7.0/css/font-awesome.min.css" rel="stylesheet">
    
    <!-- Tailwind 配置 -->
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        primary: '#165DFF',
                        secondary: '#36D399',
                        neutral: '#F5F7FA',
                    },
                    fontFamily: {
                        inter: ['Inter', 'system-ui', 'sans-serif'],
                    },
                }
            }
        }
    </script>
    

    <style type="text/tailwindcss">
        @layer utilities {
            .content-auto {
                content-visibility: auto;
            }
            .text-shadow {
                text-shadow: 0 2px 4px rgba(0,0,0,0.1);
            }
            .transition-custom {
                transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
            }
        }
    </style>
    
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap');
        
        body {
            font-family: 'Inter', system-ui, sans-serif;
        }

        html {
            scroll-behavior: smooth;
        }
        
        .watermark {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            opacity: 0.05;
            font-size: 150px;
            font-weight: bold;
            pointer-events: none;
        }
    </style>
</head>
<body class="bg-neutral min-h-screen text-gray-800">
    <div class="container mx-auto px-4 py-8 max-w-4xl relative">

        <div class="watermark">求职信</div>
        
        <!-- 信头 -->
        <header class="mb-12 text-center">
            <h1 class="text-[clamp(1.8rem,5vw,2.8rem)] font-bold text-primary mb-2">求职信</h1>
            <p class="text-gray-500 text-lg">尊敬的招聘经理：</p>
        </header>
        
        <!-- 个人信息 -->
        <section class="mb-8 bg-white rounded-xl shadow-lg p-6 relative overflow-hidden">
            <div class="absolute top-0 right-0 w-20 h-20 bg-primary/10 rounded-bl-full"></div>
            
            <div class="flex flex-col md:flex-row items-center gap-6">
                <div class="w-24 h-24 rounded-full overflow-hidden border-4 border-primary/20 shadow-md">
                    <img src="https://picsum.photos/200/200?random=1" alt="" class="w-full h-full object-cover">
                </div>
                
                <div class="text-center md:text-left">
                    <h2 class="text-[clamp(1.5rem,3vw,2rem)] font-bold text-gray-800">张三</h2>
                    <p class="text-gray-600 mb-2">应聘：Java开发</p>
                    
                    <div class="flex flex-wrap justify-center md:justify-start gap-3 text-sm text-gray-600">
                        <span class="flex items-center"><i class="fa fa-envelope-o mr-2 text-primary"></i> example@mail.com</span>
                        <span class="flex items-center"><i class="fa fa-phone mr-2 text-primary"></i> 13800138000</span>
                        <span class="flex items-center"><i class="fa fa-map-marker mr-2 text-primary"></i> 江苏省</span>
                    </div>
                </div>
            </div>
        </section>
        
        <!-- 正文内容 -->
        <main class="space-y-8">
            <!-- 求职意向 -->
            <section class="bg-white rounded-xl shadow-lg p-6 transition-custom hover:shadow-xl">
                <h3 class="text-xl font-semibold mb-4 flex items-center">
                    <i class="fa fa-bullseye text-primary mr-2"></i> 求职意向
                </h3>
                <p class="leading-relaxed">
                    您好！应届毕业生张三，非常荣幸能够应聘贵公司的前端开发工程师岗位。通过对贵公司的了解，我被贵公司在互联网领域的创新精神和技术实力所吸引，相信贵公司能够为我提供广阔的发展空间。
                </p>
            </section>
            
            <!-- 自我介绍 -->
            <section class="bg-white rounded-xl shadow-lg p-6 transition-custom hover:shadow-xl">
                <h3 class="text-xl font-semibold mb-4 flex items-center">
                    <i class="fa fa-user text-primary mr-2"></i> 自我介绍
                </h3>
                <p class="leading-relaxed">
                    在大学期间，我系统学习了计算机相关课程，并通过自学深入掌握了前端开发技术。我具备扎实的HTML/CSS/JavaScript基础，积累了丰富的项目经验。
                </p>
                <p class="leading-relaxed mt-3">
                    我热爱前端开发，关注行业最新技术动态，具有良好的学习能力和问题解决能力。我注重代码质量和用户体验，追求技术与设计的完美结合。
                </p>
            </section>
            

            <!-- 项目经验 -->
            <section class="bg-white rounded-xl shadow-lg p-6 transition-custom hover:shadow-xl">
                <h3 class="text-xl font-semibold mb-4 flex items-center">
                    <i class="fa fa-briefcase text-primary mr-2"></i> 项目经验
                </h3>
                
                <div class="space-y-4">
                    <div class="border-l-4 border-primary pl-4 pb-4">
                        <div class="flex flex-wrap items-center justify-between gap-2 mb-2">
                            <h4 class="font-semibold">校园在线商城系统</h4>
                            <span class="text-sm text-gray-500 bg-gray-100 px-2 py-1 rounded">2022.03 - 2022.06</span>
                        </div>
                        <p class="text-sm text-gray-600 mb-2">负责前端页面开发与交互实现，使用React + TypeScript技术栈</p>
                        <ul class="text-sm text-gray-600 list-disc pl-5 space-y-1">
                        </ul>
                    </div>
                    
                    <div class="border-l-4 border-primary/60 pl-4">
                        <div class="flex flex-wrap items-center justify-between gap-2 mb-2">
                            <h4 class="font-semibold">企业官网重构</h4>
                            <span class="text-sm text-gray-500 bg-gray-100 px-2 py-1 rounded">2021.10 - 2021.12</span>
                        </div>
                        <p class="text-sm text-gray-600 mb-2"></p>
                        <ul class="text-sm text-gray-600 list-disc pl-5 space-y-1">
                        </ul>
                    </div>
                </div>
            </section>
            
            <!-- 结尾 -->
            <section class="bg-white rounded-xl shadow-lg p-6 transition-custom hover:shadow-xl">
                <h3 class="text-xl font-semibold mb-4 flex items-center">
                    <i class="fa fa-handshake-o text-primary mr-2"></i> 结尾
                </h3>
                <p class="leading-relaxed">
                    我相信自己的专业知识和实践经验能够胜任贵公司的前端开发工作，并且愿意不断学习和进步，为公司的发展贡献自己的力量。如果能够加入贵公司，我将以高度的责任感和敬业精神投入工作，努力实现自身价值与公司目标的共同发展。
                </p>
                <p class="leading-relaxed mt-3">
                    感谢您在百忙之中阅读我的求职信，期待有机会与您进一步沟通。
                </p>
                <div class="mt-6 text-right">
                    <p class="font-medium">此致</p>
                    <p class="font-medium mt-1">敬礼！</p>
                    <p class="font-semibold mt-4">求职者：张三</p>
                    <p class="text-gray-500">2023年X月X日</p>
                </div>
            </section>
        </main>
        

        backToTopButton.addEventListener('click', () => {
            window.scrollTo({
                top: 0,
                behavior: 'smooth'
            });
        });
    </script>
</body>
</html>
