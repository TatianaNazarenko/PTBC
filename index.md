[old page](old.md)

Models
<details>
  <summary>SPTB</summary>
  <br> (the same as the previous one)
  <br>
  <pre>
    | Type                 | AUC (95% CI)        | Final model                                |
    |----------------------|---------------------|--------------------------------------------|       
    | proteomic            | 0.729 (0.540-0.917) | PGLYRP2, KLKB1                             |

  </pre>
</details>

1. SPTB
- excluded features 
2. SPTB
- excluded samples PBI == 1 and CL < 0.25 == 1 					
3. SPTB  or PBI						
4. SPTB or CL < 0.25						
5. PBI						
6. PBI (
- excluded samples SPTB == 1
7. CL < 0.25						
8. CL < 0.25 
- excluded SPTB == 1
9. PBI 					
10. CL < 0.25 investigate "Largest.length","Depth", "Width.Largest", "RMT", "AMT"	


![Image](./data/multiparam_glm.png)

![Image](./data/one_param_tests.png)

![Image](./data/1common.png)
![Image](./data/2common.png)
![Image](./data/3common.png)
![Image](./data/4common.png)
![Image](./data/5common.png)
![Image](./data/6common.png)
![Image](./data/7common.png)
![Image](./data/8common.png)
![Image](./data/9common.png)
![Image](./data/10common.png)



