# Dmitry #ــــــــــــــــــــــــــــــــــــــــــــــــــ#
#import webbrowser
#webbrowser.open('tiktok.com/@ali.capcuteur ') #اشتراك اجباري
#ــــــــــــــــــــــــــــــــــــــــــــــــــ#
#ــــــــــــــــــــــــــــــــــــــــــــــــــ#
import marshal #المكاتب المطلوبه
#ــــــــــــــــــــــــــــــــــــــــــــــــــ# الالوان
L = '\x1b[1;33m'
C = '\x1b[1;97m'
B = '\x1b[2;36m'
Y = '\x1b[1;34m'
C = '\x1b[1;97m'
X = '\x1f' 
G = '\x1b[1;32m'
R = '\x1b[1;31m'
r = "\033[31;1m"
g = "\033[32;1m"
y = "\033[33;1m"
p = "\033[35;1m"
w = "\033[0;1m"
#ــــــــــــــــــــــــــــــــــــــــــــــــــ#
print('DECODE BY Mazeni | @S_X_9_9 •')
print(Y +'Follow me in telegram @its_mazeni')
#print(R +'Follow us in telegram : @Ali_capcuteur ')
#print(G +'Follow us in YouTube : @S_X_9_0/@Mazeni')
#print(p + "آلَمبِرمَجِ @S_X_9_9 ")
#print(R + "آدِآهِ تّشٍفِّيِّر آدِوِآتّ نِوِعٌ مَآرشٍآلَ")
print('—————————————————————————\n\n—————————————————————————')
file = input("\033[35;1m* آدِخَلَ مََّسآر آلَمَلَفِّ آلَمَرآدِ تّشٍفِّيِّرهِ *")

m1 = open(file).read()
m2 = compile(m1, "","exec")
m3 = marshal.dumps(m2)

start = open(file + '-marshal', 'w')
start.write("\nimport marshal\n")
start.write("exec(marshal.loads("+repr(m3)+ "))")
start.close()
print("\033[2;32m [✓] تّمَ آلَتّشٍفِّيِّر بِنِجِآحٌ💥 ")
