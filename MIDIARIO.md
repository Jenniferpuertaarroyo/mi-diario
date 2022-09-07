# DIARIO
    SUB SENA
    MSGBOX "hola "
    end sub 
    
### 26 de agosto

    ´´´´

        Sub impuesto()
            m = Int(InputBox("valor a pagar anual"))
            
            Total = m * ip
            
            If m > 0 And m < 1000 Then
            MsgBox " no pagar impuesto"
            
            Else
            If m > 1001 And m < 10000 Then
                ip = 0.05
                Total = m * ip
                
                MsgBox " el resultado es: " & Total
                
            Else
                If m > 10001 And m < 100000 Then
                ip = 0.1
                Total = m * ip
                
                MsgBox " el resultado es: " & Total
                
                Else
                    If m > 100001 And m < 1000000 Then
                        ip = 0.15
                        Total = m * ip
                        
                        MsgBox " el resultado es: " & Total
                    
                    Else
                        If m > 1000001 And m < 10000000 Then
                        ip = 0.2
                        Total = m * ip
                        
                        MsgBox " el resultado es: " & Total
                            
                        Else
                        If p > 10000001 And m < 100000000 Then
                            ip = 0.25
                            Total = m * ip
                        
                        MsgBox " el resultado es: " & Total
                        
                        End If
                        End If
                    End If
                End If
            End If
            End If
        End Sub

# variable
~~~
    sub nombre()
        nom = "luis"
        num = 10
        msgbox nom
    end sub
