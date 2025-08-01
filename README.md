# Eagle Movie

Eagle Movie is a web application designed to search and explore movies and TV shows using The Movie Database (TMDb) API. It features a sleek, modern interface with multilingual support (Persian, English, Chinese) and responsive design, allowing users to browse, filter, and view detailed information about movies and TV shows.

## Features

- **Multilingual Support**: Interface available in Persian, English, and Chinese.
- **Search and Filter**: Search for movies or TV shows by title, genre, or sort by popularity, rating, or release date.
- **Detailed Information**: View comprehensive details including posters, ratings, genres, cast, videos, backdrops, posters, and reviews.
- **Responsive Design**: Optimized for both desktop and mobile devices.
- **Interactive UI**: Includes a glass-morphism effect, hover animations, and a modal for detailed content.
- **Dynamic Tabs**: Switch between info, cast, media, and reviews in the details modal.

## Technologies Used

- **HTML5**: For structuring the web content.
- **Tailwind CSS**: For styling with a utility-first approach.
- **JavaScript**: For dynamic functionality and API integration.
- **TMDb API**: For fetching movie and TV show data.
- **Google Fonts**: Vazirmatn for Persian and Noto Serif SC for Chinese text rendering.

## Setup and Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/eagle-movie.git
   ```
2. **Navigate to the Project Directory**:
   ```bash
   cd eagle-movie
   ```
3. **Open `index.html`**:
   Open the `index.html` file in a web browser. No additional server setup is required as the application uses CDN-hosted dependencies (Tailwind CSS, Google Fonts).

4. **API Key**:
   - The application uses a TMDb API key. The current key is embedded in the script for demonstration purposes. For production, replace the `API_KEY` in the JavaScript code with your own TMDb API key.
   - To get a TMDb API key, sign up at [The Movie Database](https://www.themoviedb.org/) and generate an API key.

## Usage

- **Select Language**: Use the dropdown in the header to switch between Persian, English, or Chinese.
- **Search**: Enter a movie or TV show title in the search bar and press the search button.
- **Filter**: Choose a genre or sort option to refine the results.
- **View Details**: Click the "View Full Details" button on any movie/TV show card to open a modal with detailed information.
- **Load More**: Click the "Load More" button to fetch additional results.

## Project Structure

```
eagle-movie/
│
├── index.html        # Main HTML file with the application structure and logic
└── README.md         # This file
```

## Contributing

Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

# ایگل مووی

ایگل مووی یک برنامه وب است که برای جستجو و کاوش در فیلم‌ها و سریال‌ها با استفاده از API پایگاه داده فیلم (TMDb) طراحی شده است. این برنامه دارای رابط کاربری مدرن و شیک با پشتیبانی از چند زبان (فارسی، انگلیسی، چینی) و طراحی پاسخگو است که به کاربران امکان می‌دهد فیلم‌ها و سریال‌ها را مرور کرده، فیلتر کنند و اطلاعات جامعی درباره آن‌ها مشاهده کنند.

## ویژگی‌ها

- **پشتیبانی چندزبانه**: رابط کاربری به زبان‌های فارسی، انگلیسی و چینی در دسترس است.
- **جستجو و فیلتر**: جستجو بر اساس عنوان فیلم یا سریال، ژانر یا مرتب‌سازی بر اساس محبوبیت، امتیاز یا تاریخ انتشار.
- **اطلاعات جامع**: مشاهده جزئیات کامل شامل پوستر، امتیاز، ژانرها، بازیگران، ویدیوها، تصاویر پس‌زمینه، پوسترها و نقدها.
- **طراحی پاسخگو**: بهینه‌سازی شده برای دستگاه‌های دسکتاپ و موبایل.
- **رابط کاربری تعاملی**: شامل افکت شیشه‌ای، انیمیشن‌های هاور و مدال برای نمایش محتوای دقیق.
- **تب‌های پویا**: امکان جابجایی بین اطلاعات کلی، بازیگران، رسانه و نقدها در مدال جزئیات.

## فناوری‌های استفاده شده

- **HTML5**: برای ساختاردهی محتوای وب.
- **Tailwind CSS**: برای استایل‌دهی با رویکرد ابزارمحور.
- **جاوااسکریپت**: برای عملکردهای پویا و یکپارچه‌سازی با API.
- **API TMDb**: برای دریافت داده‌های فیلم و سریال.
- **فونت‌های گوگل**: فونت وزيرمتین برای متن فارسی و Noto Serif SC برای متن چینی.

## راه‌اندازی و نصب

1. **کلون کردن مخزن**:
   ```bash
   git clone https://github.com/your-username/eagle-movie.git
   ```
2. **ورود به پوشه پروژه**:
   ```bash
   cd eagle-movie
   ```
3. **باز کردن فایل `index.html`**:
   فایل `index.html` را در مرورگر وب باز کنید. نیازی به راه‌اندازی سرور اضافی نیست زیرا برنامه از وابستگی‌های میزبانی‌شده در CDN (مانند Tailwind CSS و Google Fonts) استفاده می‌کند.

4. **کلید API**:
   - برنامه از یک کلید API TMDb استفاده می‌کند. کلید فعلی برای اهداف نمایشی در اسکریپت قرار داده شده است. برای استفاده در تولید، کلید `API_KEY` را در کد جاوااسکریپت با کلید API TMDb خود جایگزین کنید.
   - برای دریافت کلید API TMDb، در [پایگاه داده فیلم](https://www.themoviedb.org/) ثبت‌نام کرده و یک کلید API ایجاد کنید.

## استفاده

- **انتخاب زبان**: از منوی کشویی در هدر برای جابجایی بین زبان‌های فارسی، انگلیسی یا چینی استفاده کنید.
- **جستجو**: عنوان فیلم یا سریال را در نوار جستجو وارد کرده و دکمه جستجو را فشار دهید.
- **فیلتر**: ژانر یا گزینه مرتب‌سازی را برای بهبود نتایج انتخاب کنید.
- **مشاهده جزئیات**: روی دکمه "نمایش کامل جزئیات" روی کارت هر فیلم یا سریال کلیک کنید تا مدال با اطلاعات دقیق باز شود.
- **بارگذاری بیشتر**: روی دکمه "بارگذاری بیشتر" کلیک کنید تا نتایج بیشتری دریافت شود.

## ساختار پروژه

```
eagle-movie/
│
├── index.html        # فایل اصلی HTML با ساختار و منطق برنامه
└── README.md         # این فایل
```

## مشارکت

مشارکت‌ها استقبال می‌شود! برای مشارکت:
1. مخزن را فورک کنید.
2. یک شاخه جدید ایجاد کنید (`git checkout -b feature-branch`).
3. تغییرات خود را اعمال کرده و کامیت کنید (`git commit -m 'Add new feature'`).
4. به شاخه خود推送 کنید (`git push origin feature-branch`).
5. یک درخواست Pull Request ایجاد کنید.

## مجوز

این پروژه تحت مجوز MIT منتشر شده است. برای جزئیات بیشتر، فایل [LICENSE](LICENSE) را ببینید.

---

# 鹰电影

鹰电影是一个使用电影数据库（TMDb）API进行电影和电视剧搜索与探索的网页应用程序。它拥有一个现代化、时尚的界面，支持多语言（波斯语、英语、汉语），并采用响应式设计，允许用户浏览、过滤和查看有关电影和电视剧的详细信息。

## 功能

- **多语言支持**：界面支持波斯语、英语和汉语。
- **搜索与过滤**：根据标题、类型或按受欢迎程度、评分或发布日期排序进行电影或电视剧搜索。
- **详细信息**：查看包括海报、评分、类型、演员、视频、背景图片、海报和评论的全面详细信息。
- **响应式设计**：针对桌面和移动设备进行了优化。
- **交互式界面**：包括玻璃态效果、悬停动画和用于详细内容的模态窗口。
- **动态选项卡**：在详细信息模态窗口中可在概览、演员、媒体和评论之间切换。

## 使用的技术

- **HTML5**：用于构建网页内容结构。
- **Tailwind CSS**：采用实用优先的方式进行样式设计。
- **JavaScript**：用于动态功能和API集成。
- **TMDb API**：用于获取电影和电视剧数据。
- **谷歌字体**：波斯语使用Vazirmatn字体，汉语使用Noto Serif SC字体。

## 设置与安装

1. **克隆仓库**：
   ```bash
   git clone https://github.com/your-username/eagle-movie.git
   ```
2. **进入项目目录**：
   ```bash
   cd eagle-movie
   ```
3. **打开`index.html`**：
   在网页浏览器中打开`index.html`文件。由于应用程序使用CDN托管的依赖（例如Tailwind CSS和Google Fonts），无需额外的服务器设置。

4. **API密钥**：
   - 应用程序使用TMDb API密钥。当前密钥仅用于演示目的嵌入在脚本中。在生产环境中，请将JavaScript代码中的`API_KEY`替换为您自己的TMDb API密钥。
   - 要获取TMDb API密钥，请在[电影数据库](https://www.themoviedb.org/)注册并生成一个API密钥。

## 使用方法

- **选择语言**：使用页面头部下拉菜单在波斯语、英语或汉语之间切换。
- **搜索**：在搜索栏输入电影或电视剧标题，然后按搜索按钮。
- **过滤**：选择类型或排序选项以优化搜索结果。
- **查看详情**：点击任意电影或电视剧卡片上的“查看完整详情”按钮，打开包含详细信息的模态窗口。
- **加载更多**：点击“加载更多”按钮以获取更多结果。

## 项目结构

```
eagle-movie/
│
├── index.html        # 包含应用程序结构和逻辑的主HTML文件
└── README.md         # 本文件
```

## 贡献

欢迎贡献！要参与贡献：
1. 叉取仓库。
2. 创建一个新分支（`git checkout -b feature-branch`）。
3. 进行更改并提交（`git commit -m '添加新功能'`）。
4. 推送到分支（`git push origin feature-branch`）。
5. 创建一个拉取请求。

## 许可证

本项目采用MIT许可证发布。详情请见[LICENSE](LICENSE)文件。