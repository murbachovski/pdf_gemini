# 프로젝트 제목
```
PDF_Gemini
```

# 프로젝트 설명
```
PDF 파일을 Gemini를 통해서 요약 후 Docx 파일 형태로 요약본 저장
```

# 가상환경 설정
```
conda create -n arg python=3.9
```

# API_KEY 설정
```
export GENAI_API_KEY="AIzaSyDxxxxxxxxxxxxxxxxxxxx"
```

# 라이브러리 설치
```
pip install -r requirements.txt
```

# 앱 실행
```
python3 app3.py input.pdf
```

# 웹 구성
<p align="center">
  <img src="https://github.com/user-attachments/assets/df5f3ae6-889d-43df-96d0-06423136f577" width="1000">
  <img src="https://github.com/user-attachments/assets/9a199844-c392-47a7-bf17-61e3f409034d" width="1000">
  <img src="https://github.com/user-attachments/assets/ce6599f2-913d-42de-aac2-b7fd4cf14e47" width="1000">
</p>

# Ngrok
(로컬 서버 => 공개 서버로 전환)
```
<Mac M1 설치 기준>
https://ngrok.com/downloads/mac-os
brew install ngrok
ngrok config add-authtoken <token>
ngrok http 80
```

# Ngrok log
<p align="center">
  <img src="https://github.com/user-attachments/assets/5ca755c3-d8f8-4088-b3b4-1b735945d351" width="700">
</p>

# Ngrok(공개 서버 접속)
[Ngrok 공개 서버 접속](https://c83c0967a9dd.ngrok-free.app/)<br>

# Ngrok 참고 문서
[위키독스](https://cordcat.tistory.com/105)<br>

# Make requirements.txt
```
pip install pipreqs
```

# pipreqs 참고 문서
[PyPI pipreqs](https://pypi.org/project/pipreqs/)<br>

# Gemini 참고 문서
[Google AI for developer](https://ai.google.dev/gemini-api/docs/document-processing)<br>
