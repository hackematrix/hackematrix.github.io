---
title: Introduction to algorithms
date: 2024-12-12 10:00:00 +/-TTTT
categories: [Computer,algorithms]
tags: [algorithms]
---

# 插入排序
* cpp
{% highlight cpp %}
#include<iostream>
using namespace std;
#define maxn 10005
int main(){
    int n;
    cin>>n;
    int a[maxn];
    for(int i=0;i<n;i++)
        cin>>a[i];
    for(int i=1;i<n;i++){
        int key=a[i];
        int j=i-1;
        while(j>0&&a[j]>key){
            a[j+1]=a[j];
            j--;
        }
        a[j+1]=key;
    }
    for(int i=0;i<n;i++)
        cout<<a[i]<<" ";
    cout<<endl;
    return 0;
}  
{% endhighlight %}
