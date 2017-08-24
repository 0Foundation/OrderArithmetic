# OrderArithmetic
Jackaroo
1.冒泡升序
void sort (int *a ,int n)
{ 
  int i,j;
  int t;
  for (i=0;i<n-1;i++)
    {
      for(j=0;j<n-i-1;j++)
      {
        if(a[j]>a[j+1])
        {
          t=a[j];
          a[j]=a[j+1];
          a[j]+1=t;
        }
      }
    }
}
int main()
{
  int n;
  scanf("%d\n",&n);
}
