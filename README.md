# Chef-and-Masks
# cook your dish here
mask=int(input())
for m in range(mask):
  D,C = map(int, input().split())
  dispo = D*100
  cloth = C*10
  if dispo==cloth:print("cloth")
  elif dispo>cloth:print("cloth")
  else:print("disposable")
