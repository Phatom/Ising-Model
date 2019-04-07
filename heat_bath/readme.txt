输入参数文件：inp.txt
           L,neq,bins,nsamples

温度取值范围：Ts = [1,1.2,1.4,1.6,1.8,2.0,2.1,2.2,2.3,2.4,2.6,2.8,3,3.25,3.5,3.75,4,4.25,4.5,4.75,5]    

Metroplis程序： Ising.IPYNB
               模拟部分：Ising   主函数：ising()   用heat_bath
               误差计算部分：res  主函数：res() 
               绘图部分：Plot    主函数：plot() 
               拟和部分：fit     主函数：fit()
               
中间结果：L_bin.csv(各个L) bin.csv(全部)
        L,T <m> <E> cv q
        
最终数据：A_L.dat (共(4xn)个文件，A = m,e,q,cv)
        T <A> sigma_A 

拟合数据：fit.txt
        'Tc','qc','a0','v','a1','u1','w1' = ......

图形：   m-T曲线   m.png
        E-T曲线   E.png
        q-T曲线   q.png
        cv-T曲线  c.png
        
运行进度：process.txt
        记录运行到了哪一步外加废话
        running L={} T={} ib = {}
        resulting L = {}
        FINALLY ploting
        ......