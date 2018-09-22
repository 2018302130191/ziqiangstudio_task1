# ziqiangstudio_task1
from hashlib import sha256
def ec(str):
    sh=sha256()
    sh.update(str.encode())
    return sh.hexdigest()
    
if __name__=='__main__':
    qwq=ec("hello")
    print(qwq)
