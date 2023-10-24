 
; main program
;
; This program will add two numbers together and display the result.
;
main:
mov eax, 1
mov ebx, 2
mov ecx, 0
add eax, ebx
mov edx, eax
add ecx, edx
mov eax, ecx
; This is where we print the result.
;
mov eax, 4
int 0x80
