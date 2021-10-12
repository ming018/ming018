# 사이트 별로 비밀번호를 만들어 주는 프로그램을 작성하시오.

# 예) http://naver.com
# 규칙1 : http:// 부분은 제외 => naver.com
# 규칙2 : 처음 만나는 점(.) 이후 부분은 제외 => naver
# 규칙3 : 남은 글자 중 처음 세자리 + 글자 갯수 + 글자내 e 갯수 + "!"로 구성
#                 (nav)               (5)            (1)         (!)
# 예) 비밀번호 : nav51!

site=input("비밀번호를 만들고자 하는 사이트 주소를 기제하시오. : ")
if "http://" in site:
    site=site[7:]
if ".com" in site:
    site=site[:-4]
else:
    site=site
len_site=len(site)
len_e=site.count("e")

print("비밀번호 : {0}{1}{2}!".format(site,len_site,len_e))
