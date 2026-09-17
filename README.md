\documentclass[12pt,a4paper]{article}

\usepackage[utf8]{inputenc}
\usepackage[T5]{fontenc}
\usepackage[vietnamese]{babel}
\usepackage{amsmath,amssymb,amsthm,amsfonts,url}
\usepackage[a4paper,left=3cm,right=2cm,top=2.5cm,bottom=2.5cm]{geometry}
\usepackage{setspace,indentfirst}
\onehalfspacing
\setlength{\parindent}{1.25cm}
\usepackage{fancyhdr}
\pagestyle{fancy}
\fancyhf{}
\fancyfoot[C]{\thepage}
\renewcommand{\headrulewidth}{0pt}

\begin{document}

% LỜI CẢM ƠN
\begin{center}
{\Large\bfseries LỜI CẢM ƠN}
\end{center}
\vspace{0.3cm}
Để hoàn thành đề tài này, bên cạnh sự nỗ lực của bản thân, em xin bày tỏ lòng biết ơn sâu sắc đến thầy \textbf{Nguyễn Đăng Minh Phúc}. Sự hướng dẫn tận tình, sắc sảo và tâm huyết của Thầy đã giúp em vượt qua mọi vướng mắc chuyên môn, đồng thời là bài học quý giá về tư duy khoa học. Em cũng xin chân thành cảm ơn quý thầy cô Khoa Toán, gia đình và bạn bè đã luôn động viên, hỗ trợ em trong suốt quá trình học tập.
\vspace{0.5cm}
\begin{flushright}
\end{flushright}
\newpage

% LỜI MỞ ĐẦU VÀ ĐỀ CƯƠNG
\begin{center}
{\Large\bfseries LỜI MỞ ĐẦU \& ĐỀ CƯƠNG NGHIÊN CỨU}
\end{center}
\vspace{0.3cm}
Bài toán tìm giá trị lớn nhất và nhỏ nhất (GTLN - GTNN) đóng vai trò nền tảng trong toán học và các bài toán tối ưu hóa thực tiễn (kinh tế, kỹ thuật, đời sống). Chuyên đề ``Các dạng bài tập giá trị lớn nhất và giá trị nhỏ nhất của hàm số - Ứng dụng bài toán thực tế'' được chọn nhằm hệ thống hóa kiến thức và phương pháp giải quyết các bài toán tối ưu.

\section*{1. Mục tiêu nghiên cứu}
\begin{itemize}
    \item Hệ thống lý thuyết (định lý Weierstrass, đạo hàm, bất đẳng thức).
    \item Xây dựng quy trình mô hình hóa toán học từ thực tiễn.
    \item Rèn luyện kỹ năng giải toán vận dụng cao.
\end{itemize}

\section*{2. Đối tượng và Phạm vi nghiên cứu}
\begin{itemize}
    \item Đối tượng\textbf{:} Lý thuyết GTLN - GTNN chương trình Toán 12 và các bài toán tối ưu thực tế.
    \item Phạm vi: Chuyên đề đạo hàm ứng dụng GTLN - GTNN trong hình học không gian, kinh tế và vật lý.
\end{itemize}

\section*{3. Thời gian nghiên cứu}
\begin{itemize}
    \item Thời gian thực hiện: 2 tuần.
\end{itemize}

\newpage
\tableofcontents
\newpage

% TÓM TẮT NỘI DUNG CHÍNH
\begin{center}
{\Large\bfseries TÓM TẮT NỘI DUNG CHÍNH}
\end{center}

\section{Cơ sở lý thuyết}
\begin{itemize}
    \item Định nghĩa, ý nghĩa thực tiễn của hàm số và GTLN - GTNN.
    \item Phân biệt cực trị và GTLN - GTNN.
    \item Định lý Weierstrass và các phương pháp giải (tính đơn điệu, đạo hàm, bảng biến thiên, bất đẳng thức AM-GM).
\end{itemize}

\section{Bài toán tối ưu hóa thực tiễn}
\begin{itemize}
    \item Bản chất và quy trình 4 bước giải bài toán tối ưu (chọn ẩn, lập hàm mục tiêu, khảo sát, kết luận).
    \item Các ứng dụng phổ biến: Tối ưu hình học (diện tích, thể tích), kinh tế (lợi nhuận, chi phí biên), vận chuyển và chuyển động vật lý.
\end{itemize}

\section{Một số bài toán thực tế tiêu biểu}
\begin{itemize}
    \item \textbf{Bài toán máng xối:} Góc uốn tối ưu $\theta = \dfrac{\pi}{3}$.
    \item \textbf{Bài toán lợi nhuận công ty:} Sản lượng tối ưu $x = 350$, lợi nhuận max $30.625.000$ đồng.
    \item \textbf{Bài toán chuyển động:} Tốc độ chất điểm lớn nhất tại $t = 6\text{ s}$ ($7,92\text{ m/s}$).
    \item \textbf{Bài toán hộp không nắp:} Cạnh $x = 2\text{ cm}$, thể tích max $128\text{ cm}^3$.
    \item \textbf{Bài toán khí quản:} Bán kính tối ưu $r = \dfrac{2}{3}R$.
\end{itemize}

\newpage

% TÀI LIỆU THAM KHẢO
\begin{center}
{\Large\bfseries TÀI LIỆU THAM KHẢO}
\addcontentsline{toc}{section}{Tài liệu tham khảo}
\end{center}
\vspace{0.5cm}
\begin{enumerate}
    \item TOANMATH.com (2024, 2025), \emph{Các chuyên đề GTLN - GTNN và toán thực tế}.
    \item Tailieuonthi.org, \emph{Toán thực tế chuyên đề GTLN - GTNN hàm số}.
    \item Th.S Đặng Việt Đông, \emph{Tài liệu ôn tập toán lớp 12 theo chuyên đề}.
\end{enumerate}

\end{document}
