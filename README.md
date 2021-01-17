# car_plate_detection
자동차 번호판 검출

# 1. 한국어 인식팩 다운
# https://github.com/tesseract-ocr/tessdata/blob/master/kor.traineddata

# 2. tesseract 다운
# https://digi.bib.uni-mannheim.de/tesseract/

# 3. tesseract 폴더 안에 한국어 인식팩을 넣어줌
# C:\Program Files\Tesseract-OCR\tessdata

# 4. 아래 코드에서 tesseract 시작전 파일 위치 변경
# pytesseract.pytesseract.tesseract_cmd = r'C:\Program Files\Tesseract-OCR\tesseract.exe'
