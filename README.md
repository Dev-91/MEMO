# 폴더(디렉토리) 생성하기
mkdir <폴더 이름>	# ex) mkdir dev91
mkdir <디렉토리>	# ex) mkdir ~/Documents/dev91 

# 저장소 가져오기
git clone <URL>.git

# Git 초기화하기
git init

# Git 사용자 설정
git config user.name <사용자 이름>
git config user.email <사용자 이메일>

# Git 가져오기
git clone <URL>.git

# 저장소 URL 설정하기
git remote -v					# 저장소 URL 확인
git remote add <저장소 이름> <URL>.git		# 저장소 URL 추가
git remote delete <저장소 이름>			# 저장소 URL 삭제
git remote set-url <저장소 이름> <URL>.git	# 저장소 URL 수정

# 상태 확인
git status

# 수정 사항 확정하기
git add <파일 이름>		# 수정된 파일을 저장소에 올릴 준비
git add .			# 수정된 전체 파일을 저장소에 올릴 준비
git commit -m "커밋 내용"	# add한 수정된 파일을 저장소에 올릴 것을 확정

# 수정 사항을 저장소에 반영하기
git push <저장소 이름> master

# 수정된 저장소 내용 불러오기
git pull <저장소 이름> master
