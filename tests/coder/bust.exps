	.data	
	.comm	u,17916
n:	.long	0
	.text	
	.globl	ptmain
ptmain:	pushl	%ebp
	movl	%esp, %ebp	
	movl	$1,u+0
	movl	$2,u+4
	movl	$1,u+8
	movl	$7,u+12
	movl	$1,u+44
	movl	$7,u+48
	jmp	f1
p40:	pushl	%ebp
	movl	%esp, %ebp	
	movl	8(%ebp),%eax
	movl	%eax,u+1152
	movl	12(%ebp),%eax
	movl	%eax,u+1148
	movl	$37,n
	cmpl	$17,u+1144
	jne	f2
	incl	n
	movl	$19,u+1144
	jmp	f3
f2:	movl	$40,n
	movl	$17,u+1144
f3:	movl	$42,n
	movl	u+1140,%eax
	imull	u+1144,%eax
	movl	$10000,%esi
	movl	%eax,%edi
	pushl	%eax
	pushl	%edx
	movl	%edi,%edx
	movl	%edx,%eax
	sarl	$31,	%edx
	idivl	%esi
	movl	%edx,%esi
	popl	%edx
	popl	%eax
	movl	%esi,%eax
	movl	%eax,u+1140
	incl	n
	movl	u+1148,%eax
	movl	u+1152,%ebx
	movl	%ebx,%esi
	movl	u+1140,%ebx
	movl	%ebx,%edi
	pushl	%eax
	pushl	%edx
	movl	%edi,%edx
	movl	%edx,%eax
	sarl	$31,	%edx
	idivl	%esi
	movl	%edx,%esi
	popl	%edx
	popl	%eax
	movl	%esi,%ebx
	incl	%ebx
	movl	%ebx,(%eax)
	leave	
	ret	
f1:	movl	$47,n
	movl	$13277,u+1140
	incl	n
	movl	$17,u+1144
	movl	$1,u+1156
	movl	$52,u+1160
	jmp	f4
p151:	pushl	%ebp
	movl	%esp, %ebp	
	movl	$1,u+1380
	movl	$13,u+1384
	movl	$66,n
	movl	$1,u+1444
b5:	movl	$68,n
	movl	u+1444,%eax
	cmpl	$13,%eax
	jle	f6
	cmpl	$1,%eax
	jge	f7
	pushl	n
	call	pttrap13
f7:f6:	decl	%eax
	shl	$2,%eax
	lea	u+1388,%ebx
	addl	%ebx,%eax
	movl	$0,(%eax)
	incl	n
	incl	u+1444
	cmpl	$13,u+1444
	jg	f8
	jmp	b5
f8:	movl	$73,n
	movl	$1,u+1440
b9:	movl	$75,n
	lea	u+1376,%eax
	pushl	%eax
	pushl	$13
	call	p40
	addl	$8,%esp
	movl	$76,n
b10:	movl	$76,n
	movl	u+1376,%eax
	cmpl	$13,%eax
	jle	f11
	cmpl	$1,%eax
	jge	f12
	pushl	n
	call	pttrap13
f12:f11:	decl	%eax
	shl	$2,%eax
	lea	u+1388,%ebx
	addl	%ebx,%eax
	cmpl	$4,(%eax)
	jne	f13
	incl	n
	lea	u+1376,%eax
	pushl	%eax
	pushl	$13
	call	p40
	addl	$8,%esp
	movl	$78,n
	jmp	b10
f13:	movl	$80,n
	movl	u+1440,%eax
	cmpl	$52,%eax
	jle	f14
	cmpl	$1,%eax
	jge	f15
	pushl	n
	call	pttrap13
f15:f14:	decl	%eax
	shl	$2,%eax
	lea	u+1164,%ebx
	addl	%ebx,%eax
	movl	u+1376,%ebx
	movl	%ebx,(%eax)
	incl	n
	movl	u+1376,%eax
	cmpl	$13,%eax
	jle	f16
	cmpl	$1,%eax
	jge	f17
	pushl	n
	call	pttrap13
f17:f16:	decl	%eax
	shl	$2,%eax
	lea	u+1388,%ebx
	addl	%ebx,%eax
	movl	u+1376,%ebx
	cmpl	$13,%ebx
	jle	f18
	cmpl	$1,%ebx
	jge	f19
	pushl	n
	call	pttrap13
f19:f18:	decl	%ebx
	shl	$2,%ebx
	lea	u+1388,%ecx
	addl	%ecx,%ebx
	movl	(%ebx),%ebx
	incl	%ebx
	movl	%ebx,(%eax)
	movl	$83,n
	incl	u+1440
	cmpl	$52,u+1440
	jg	f20
	jmp	b9
f20:	movl	$87,n
	movl	$0,u+1372
	leave	
	ret	
p350:	pushl	%ebp
	movl	%esp, %ebp	
	movl	8(%ebp),%eax
	movl	%eax,u+1448
	movl	$91,n
	incl	u+1372
	incl	n
	movl	u+1448,%eax
	movl	u+1372,%ebx
	cmpl	$52,%ebx
	jle	f21
	cmpl	$1,%ebx
	jge	f22
	pushl	n
	call	pttrap13
f22:f21:	decl	%ebx
	shl	$2,%ebx
	lea	u+1164,%ecx
	addl	%ecx,%ebx
	movl	(%ebx),%ebx
	movl	%ebx,(%eax)
	leave	
	ret	
p388:	pushl	%ebp
	movl	%esp, %ebp	
	movl	8(%ebp),%eax
	movl	%eax,u+1452
	movl	$96,n
	movl	u+1452,%eax
	movl	$52,%ebx
	subl	u+1372,%ebx
	incl	%ebx
	movl	%ebx,(%eax)
	leave	
	ret	
f4:	movl	$1,u+1456
	movl	$13,u+1460
	jmp	f23
p425:	pushl	%ebp
	movl	%esp, %ebp	
	movl	8(%ebp),%eax
	movl	%eax,u+14784
	movl	12(%ebp),%eax
	movl	%eax,u+14780
	movl	16(%ebp),%eax
	movl	%eax,u+14776
	movl	$109,n
	movl	u+14784,%eax
	.data	
s447:	.asciz	""
	.text	
	lea	s447,%ebx
	pushl	%eax
	pushl	%ebx
	pushl	%ecx
	pushl	%edx
	movl	%ebx,%ecx
	pushl	%ecx
	pushl	%eax
	call	pttrap101
	addl	$8,%esp
	popl	%edx
	popl	%ecx
	popl	%ebx
	popl	%eax
	movl	$111,n
	movl	$1,u+14792
b24:	movl	$112,n
	movl	u+14776,%eax
	cmpl	%eax,u+14792
	jg	f25
	incl	n
	movl	u+14784,%eax
	movl	u+14784,%ebx
	.data	
s478:	.asciz	" "
	.text	
	lea	s478,%ecx
	pushl	%eax
	pushl	%ebx
	pushl	%ecx
	pushl	%edx
	movl	%ecx,%edx
	pushl	%edx
	pushl	%ebx
	call	pttrap103
	addl	$8,%esp
	movl	%eax,%esi
	popl	%edx
	popl	%ecx
	popl	%ebx
	popl	%eax
	movl	%esi,%ebx
	movl	u+14780,%ecx
	movl	u+14792,%edx
	cmpl	4(%ecx),%edx
	jle	f26
	cmpl	(%ecx),%edx
	jge	f27
	pushl	n
	call	pttrap13
f27:f26:	subl	(%ecx),%edx
	shl	$2,%edx
	addl	$8,%ecx
	addl	%ecx,%edx
	movl	(%edx),%edx
	cmpl	$13,%edx
	jle	f28
	cmpl	$1,%edx
	jge	f29
	pushl	n
	call	pttrap13
f29:f28:	decl	%edx
	shl	$10,%edx
	lea	u+1464,%ecx
	addl	%ecx,%edx
	pushl	%eax
	pushl	%ebx
	pushl	%ecx
	pushl	%edx
	pushl	%edx
	movl	%ebx,%ecx
	pushl	%ecx
	call	pttrap103
	addl	$8,%esp
	movl	%eax,%esi
	popl	%edx
	popl	%ecx
	popl	%ebx
	popl	%eax
	movl	%esi,%ebx
	pushl	%eax
	pushl	%ebx
	pushl	%ecx
	pushl	%edx
	movl	%ebx,%ecx
	pushl	%ecx
	pushl	%eax
	call	pttrap101
	addl	$8,%esp
	popl	%edx
	popl	%ecx
	popl	%ebx
	popl	%eax
	incl	n
	incl	u+14792
	jmp	b24
f25:	leave	
	ret	
f23:	movl	$119,n
	.data	
s528:	.asciz	"A"
	.text	
	lea	s528,%eax
	pushl	%eax
	pushl	%ebx
	pushl	%ecx
	pushl	%edx
	movl	%eax,%ebx
	pushl	%ebx
	lea	u+1464,%eax
	pushl	%eax
	call	pttrap101
	addl	$8,%esp
	popl	%edx
	popl	%ecx
	popl	%ebx
	popl	%eax
	incl	n
	.data	
s541:	.asciz	"2"
	.text	
	lea	s541,%eax
	pushl	%eax
	pushl	%ebx
	pushl	%ecx
	pushl	%edx
	movl	%eax,%ebx
	pushl	%ebx
	lea	u+2488,%eax
	pushl	%eax
	call	pttrap101
	addl	$8,%esp
	popl	%edx
	popl	%ecx
	popl	%ebx
	popl	%eax
	incl	n
	.data	
s554:	.asciz	"3"
	.text	
	lea	s554,%eax
	pushl	%eax
	pushl	%ebx
	pushl	%ecx
	pushl	%edx
	movl	%eax,%ebx
	pushl	%ebx
	lea	u+3512,%eax
	pushl	%eax
	call	pttrap101
	addl	$8,%esp
	popl	%edx
	popl	%ecx
	popl	%ebx
	popl	%eax
	incl	n
	.data	
s567:	.asciz	"4"
	.text	
	lea	s567,%eax
	pushl	%eax
	pushl	%ebx
	pushl	%ecx
	pushl	%edx
	movl	%eax,%ebx
	pushl	%ebx
	lea	u+4536,%eax
	pushl	%eax
	call	pttrap101
	addl	$8,%esp
	popl	%edx
	popl	%ecx
	popl	%ebx
	popl	%eax
	incl	n
	.data	
s580:	.asciz	"5"
	.text	
	lea	s580,%eax
	pushl	%eax
	pushl	%ebx
	pushl	%ecx
	pushl	%edx
	movl	%eax,%ebx
	pushl	%ebx
	lea	u+5560,%eax
	pushl	%eax
	call	pttrap101
	addl	$8,%esp
	popl	%edx
	popl	%ecx
	popl	%ebx
	popl	%eax
	incl	n
	.data	
s593:	.asciz	"6"
	.text	
	lea	s593,%eax
	pushl	%eax
	pushl	%ebx
	pushl	%ecx
	pushl	%edx
	movl	%eax,%ebx
	pushl	%ebx
	lea	u+6584,%eax
	pushl	%eax
	call	pttrap101
	addl	$8,%esp
	popl	%edx
	popl	%ecx
	popl	%ebx
	popl	%eax
	incl	n
	.data	
s606:	.asciz	"7"
	.text	
	lea	s606,%eax
	pushl	%eax
	pushl	%ebx
	pushl	%ecx
	pushl	%edx
	movl	%eax,%ebx
	pushl	%ebx
	lea	u+7608,%eax
	pushl	%eax
	call	pttrap101
	addl	$8,%esp
	popl	%edx
	popl	%ecx
	popl	%ebx
	popl	%eax
	incl	n
	.data	
s619:	.asciz	"8"
	.text	
	lea	s619,%eax
	pushl	%eax
	pushl	%ebx
	pushl	%ecx
	pushl	%edx
	movl	%eax,%ebx
	pushl	%ebx
	lea	u+8632,%eax
	pushl	%eax
	call	pttrap101
	addl	$8,%esp
	popl	%edx
	popl	%ecx
	popl	%ebx
	popl	%eax
	incl	n
	.data	
s632:	.asciz	"9"
	.text	
	lea	s632,%eax
	pushl	%eax
	pushl	%ebx
	pushl	%ecx
	pushl	%edx
	movl	%eax,%ebx
	pushl	%ebx
	lea	u+9656,%eax
	pushl	%eax
	call	pttrap101
	addl	$8,%esp
	popl	%edx
	popl	%ecx
	popl	%ebx
	popl	%eax
	incl	n
	.data	
s645:	.asciz	"10"
	.text	
	lea	s645,%eax
	pushl	%eax
	pushl	%ebx
	pushl	%ecx
	pushl	%edx
	movl	%eax,%ebx
	pushl	%ebx
	lea	u+10680,%eax
	pushl	%eax
	call	pttrap101
	addl	$8,%esp
	popl	%edx
	popl	%ecx
	popl	%ebx
	popl	%eax
	incl	n
	.data	
s659:	.asciz	"J"
	.text	
	lea	s659,%eax
	pushl	%eax
	pushl	%ebx
	pushl	%ecx
	pushl	%edx
	movl	%eax,%ebx
	pushl	%ebx
	lea	u+11704,%eax
	pushl	%eax
	call	pttrap101
	addl	$8,%esp
	popl	%edx
	popl	%ecx
	popl	%ebx
	popl	%eax
	incl	n
	.data	
s672:	.asciz	"Q"
	.text	
	lea	s672,%eax
	pushl	%eax
	pushl	%ebx
	pushl	%ecx
	pushl	%edx
	movl	%eax,%ebx
	pushl	%ebx
	lea	u+12728,%eax
	pushl	%eax
	call	pttrap101
	addl	$8,%esp
	popl	%edx
	popl	%ecx
	popl	%ebx
	popl	%eax
	incl	n
	.data	
s685:	.asciz	"K"
	.text	
	lea	s685,%eax
	pushl	%eax
	pushl	%ebx
	pushl	%ecx
	pushl	%edx
	movl	%eax,%ebx
	pushl	%ebx
	lea	u+13752,%eax
	pushl	%eax
	call	pttrap101
	addl	$8,%esp
	popl	%edx
	popl	%ecx
	popl	%ebx
	popl	%eax
	jmp	f30
p691:	pushl	%ebp
	movl	%esp, %ebp	
	movl	8(%ebp),%eax
	movl	%eax,u+14796
	movl	$140,n
	movl	$0,u+96
	incl	n
	movl	$0,u+92
	incl	n
	movl	$0,u+88
	incl	n
	pushl	u+4
	call	pttrap6
	addl	$4,%esp
	pushl	u+4
	call	pttrap6
	addl	$4,%esp
	incl	n
	pushl	u+4
	.data	
s745:	.asciz	"New shuffle."
	.text	
	lea	s745,%eax
	pushl	%eax
	pushl	$1
	call	pttrap109
	addl	$12,%esp
	pushl	u+4
	call	pttrap6
	addl	$4,%esp
	incl	n
	pushl	u+4
	call	pttrap6
	addl	$4,%esp
	incl	n
	pushl	u+4
	.data	
s790:	.asciz	"Enter player name (E.O.Thorp for Thorp, your name for you, q to quit): "
	.text	
	lea	s790,%eax
	pushl	%eax
	pushl	$1
	call	pttrap109
	addl	$12,%esp
	incl	n
	pushl	u+0
	lea	u+110,%eax
	pushl	%eax
	call	pttrap108
	addl	$8,%esp
	pushl	u+0
	call	pttrap4
	addl	$4,%esp
	movl	$149,n
	.data	
s898:	.asciz	"q"
	.text	
	lea	s898,%eax
	pushl	%eax
	pushl	%ebx
	pushl	%ecx
	pushl	%edx
	movl	%eax,%ebx
	pushl	%ebx
	lea	u+110,%eax
	pushl	%eax
	call	pttrap107
	addl	$8,%esp
	movl	%eax,%esi
	popl	%edx
	popl	%ecx
	popl	%ebx
	popl	%eax
	movl	%esi,%eax
	cmpb	$0,%al
	je	f31
	incl	n
	movl	u+14796,%eax
	movb	$0,(%eax)
	jmp	f32
f31:	movl	$153,n
	.data	
s923:	.asciz	"E.O.Thorp"
	.text	
	lea	s923,%eax
	pushl	%eax
	pushl	%ebx
	pushl	%ecx
	pushl	%edx
	movl	%eax,%ebx
	pushl	%ebx
	lea	u+110,%eax
	pushl	%eax
	call	pttrap107
	addl	$8,%esp
	movl	%eax,%esi
	popl	%edx
	popl	%ecx
	popl	%ebx
	popl	%eax
	movl	%esi,%eax
	cmpb	$0,%al
	jne	f33
	incl	n
	pushl	u+4
	.data	
s946:	.asciz	"What does he/she stand on? "
	.text	
	lea	s946,%eax
	pushl	%eax
	pushl	$1
	call	pttrap109
	addl	$12,%esp
	incl	n
	pushl	u+0
	lea	u+1136,%eax
	pushl	%eax
	call	pttrap10
	addl	$8,%esp
	pushl	u+0
	call	pttrap4
	addl	$4,%esp
b34:	movl	$156,n
	cmpl	$0,u+1136
	jle	f35
	cmpl	$20,u+1136
	jle	f36
f35:	incl	n
	pushl	u+4
	.data	
s1031:	.asciz	"(1..20): "
	.text	
	lea	s1031,%eax
	pushl	%eax
	pushl	$1
	call	pttrap109
	addl	$12,%esp
	incl	n
	pushl	u+0
	lea	u+1136,%eax
	pushl	%eax
	call	pttrap10
	addl	$8,%esp
	pushl	u+0
	call	pttrap4
	addl	$4,%esp
	jmp	b34
f36:f33:	movl	$160,n
	movl	$162,n
	.data	
s1084:	.asciz	"E.O.Thorp"
	.text	
	lea	s1084,%eax
	pushl	%eax
	pushl	%ebx
	pushl	%ecx
	pushl	%edx
	movl	%eax,%ebx
	pushl	%ebx
	lea	u+110,%eax
	pushl	%eax
	call	pttrap107
	addl	$8,%esp
	movl	%eax,%esi
	popl	%edx
	popl	%ecx
	popl	%ebx
	popl	%eax
	movl	%esi,%eax
	cmpb	$0,%al
	je	f37
	incl	n
	pushl	u+4
	call	pttrap6
	addl	$4,%esp
	incl	n
	pushl	u+4
	.data	
s1115:	.asciz	"E.O.Thorp plays this time."
	.text	
	lea	s1115,%eax
	pushl	%eax
	pushl	$1
	call	pttrap109
	addl	$12,%esp
	pushl	u+4
	call	pttrap6
	addl	$4,%esp
	jmp	f38
f37:	movl	$166,n
	pushl	u+4
	call	pttrap6
	addl	$4,%esp
	incl	n
	pushl	u+4
	.data	
s1178:	.asciz	"Next player is "
	.text	
	lea	s1178,%eax
	pushl	%eax
	pushl	%ebx
	pushl	%ecx
	pushl	%edx
	lea	u+110,%ebx
	pushl	%ebx
	movl	%eax,%ebx
	pushl	%ebx
	call	pttrap103
	addl	$8,%esp
	movl	%eax,%esi
	popl	%edx
	popl	%ecx
	popl	%ebx
	popl	%eax
	movl	%esi,%eax
	.data	
s1199:	.asciz	"."
	.text	
	lea	s1199,%ebx
	pushl	%eax
	pushl	%ebx
	pushl	%ecx
	pushl	%edx
	movl	%ebx,%ecx
	pushl	%ecx
	movl	%eax,%ebx
	pushl	%ebx
	call	pttrap103
	addl	$8,%esp
	movl	%eax,%esi
	popl	%edx
	popl	%ecx
	popl	%ebx
	popl	%eax
	movl	%esi,%eax
	pushl	%eax
	pushl	$1
	call	pttrap109
	addl	$12,%esp
	pushl	u+4
	call	pttrap6
	addl	$4,%esp
	incl	n
	pushl	u+4
	.data	
s1225:	.asciz	"He stops at "
	.text	
	lea	s1225,%eax
	pushl	%eax
	pushl	$1
	call	pttrap109
	addl	$12,%esp
	pushl	u+4
	pushl	u+1136
	pushl	$1
	call	pttrap8
	addl	$12,%esp
	pushl	u+4
	.data	
s1264:	.asciz	"."
	.text	
	lea	s1264,%eax
	pushl	%eax
	pushl	$1
	call	pttrap109
	addl	$12,%esp
	pushl	u+4
	call	pttrap6
	addl	$4,%esp
	movl	$170,n
	movl	$15,%eax
	cmpl	u+1136,%eax
	jle	f39
	incl	n
	pushl	u+4
	.data	
s1300:	.asciz	"(What a hamburger!)"
	.text	
	lea	s1300,%eax
	pushl	%eax
	pushl	$1
	call	pttrap109
	addl	$12,%esp
	pushl	u+4
	call	pttrap6
	addl	$4,%esp
	jmp	f40
f39:	movl	$173,n
	pushl	u+4
	.data	
s1347:	.asciz	"Good luck, "
	.text	
	lea	s1347,%eax
	pushl	%eax
	pushl	%ebx
	pushl	%ecx
	pushl	%edx
	lea	u+110,%ebx
	pushl	%ebx
	movl	%eax,%ebx
	pushl	%ebx
	call	pttrap103
	addl	$8,%esp
	movl	%eax,%esi
	popl	%edx
	popl	%ecx
	popl	%ebx
	popl	%eax
	movl	%esi,%eax
	.data	
s1364:	.asciz	"."
	.text	
	lea	s1364,%ebx
	pushl	%eax
	pushl	%ebx
	pushl	%ecx
	pushl	%edx
	movl	%ebx,%ecx
	pushl	%ecx
	movl	%eax,%ebx
	pushl	%ebx
	call	pttrap103
	addl	$8,%esp
	movl	%eax,%esi
	popl	%edx
	popl	%ecx
	popl	%ebx
	popl	%eax
	movl	%esi,%eax
	pushl	%eax
	pushl	$1
	call	pttrap109
	addl	$12,%esp
	pushl	u+4
	call	pttrap6
	addl	$4,%esp
f40:f38:	movl	$177,n
	movl	u+14796,%eax
	movb	$1,(%eax)
f32:	leave	
	ret	
p1405:	pushl	%ebp
	movl	%esp, %ebp	
	movl	8(%ebp),%eax
	movl	%eax,u+14800
	movl	$188,n
	lea	u+14804,%eax
	pushl	%eax
	call	p388
	addl	$4,%esp
	movl	$190,n
	cmpl	$10,u+14804
	jle	f41
	incl	n
	pushl	u+4
	call	pttrap6
	addl	$4,%esp
	incl	n
	pushl	u+4
	.data	
s1450:	.asciz	"New game."
	.text	
	lea	s1450,%eax
	pushl	%eax
	pushl	$1
	call	pttrap109
	addl	$12,%esp
	pushl	u+4
	call	pttrap6
	addl	$4,%esp
	incl	n
	incl	u+96
	incl	n
	movl	u+14800,%eax
	movb	$1,(%eax)
	jmp	f42
f41:	movl	$196,n
	pushl	u+4
	call	pttrap6
	addl	$4,%esp
	incl	n
	pushl	u+4
	.data	
s1517:	.asciz	"Too few cards left for another game."
	.text	
	lea	s1517,%eax
	pushl	%eax
	pushl	$1
	call	pttrap109
	addl	$12,%esp
	pushl	u+4
	call	pttrap6
	addl	$4,%esp
	incl	n
	pushl	u+4
	.data	
s1577:	.asciz	"Of "
	.text	
	lea	s1577,%eax
	pushl	%eax
	pushl	$1
	call	pttrap109
	addl	$12,%esp
	pushl	u+4
	pushl	u+96
	pushl	$1
	call	pttrap8
	addl	$12,%esp
	pushl	u+4
	.data	
s1607:	.asciz	" games, "
	.text	
	lea	s1607,%eax
	pushl	%eax
	pushl	$1
	call	pttrap109
	addl	$12,%esp
	pushl	u+4
	lea	u+110,%eax
	pushl	%eax
	pushl	$1
	call	pttrap109
	addl	$12,%esp
	pushl	u+4
	.data	
s1644:	.asciz	" won "
	.text	
	lea	s1644,%eax
	pushl	%eax
	pushl	$1
	call	pttrap109
	addl	$12,%esp
	pushl	u+4
	pushl	u+92
	pushl	$1
	call	pttrap8
	addl	$12,%esp
	pushl	u+4
	.data	
s1676:	.asciz	", dealer won "
	.text	
	lea	s1676,%eax
	pushl	%eax
	pushl	$1
	call	pttrap109
	addl	$12,%esp
	pushl	u+4
	pushl	u+88
	pushl	$1
	call	pttrap8
	addl	$12,%esp
	pushl	u+4
	.data	
s1716:	.asciz	"."
	.text	
	lea	s1716,%eax
	pushl	%eax
	pushl	$1
	call	pttrap109
	addl	$12,%esp
	incl	n
	pushl	u+4
	call	pttrap6
	addl	$4,%esp
	movl	$201,n
	movl	u+92,%eax
	cmpl	%eax,u+88
	jle	f43
	incl	n
	pushl	u+4
	.data	
s1753:	.asciz	"House cleans up on "
	.text	
	lea	s1753,%eax
	pushl	%eax
	pushl	%ebx
	pushl	%ecx
	pushl	%edx
	lea	u+110,%ebx
	pushl	%ebx
	movl	%eax,%ebx
	pushl	%ebx
	call	pttrap103
	addl	$8,%esp
	movl	%eax,%esi
	popl	%edx
	popl	%ecx
	popl	%ebx
	popl	%eax
	movl	%esi,%eax
	.data	
s1778:	.asciz	" this time."
	.text	
	lea	s1778,%ebx
	pushl	%eax
	pushl	%ebx
	pushl	%ecx
	pushl	%edx
	movl	%ebx,%ecx
	pushl	%ecx
	movl	%eax,%ebx
	pushl	%ebx
	call	pttrap103
	addl	$8,%esp
	movl	%eax,%esi
	popl	%edx
	popl	%ecx
	popl	%ebx
	popl	%eax
	movl	%esi,%eax
	pushl	%eax
	pushl	$1
	call	pttrap109
	addl	$12,%esp
	pushl	u+4
	call	pttrap6
	addl	$4,%esp
	jmp	f44
f43:	movl	$203,n
	movl	u+88,%eax
	cmpl	%eax,u+92
	jle	f45
	incl	n
	.data	
s1826:	.asciz	"E.O.Thorp"
	.text	
	lea	s1826,%eax
	pushl	%eax
	pushl	%ebx
	pushl	%ecx
	pushl	%edx
	movl	%eax,%ebx
	pushl	%ebx
	lea	u+110,%eax
	pushl	%eax
	call	pttrap107
	addl	$8,%esp
	movl	%eax,%esi
	popl	%edx
	popl	%ecx
	popl	%ebx
	popl	%eax
	movl	%esi,%eax
	cmpb	$0,%al
	je	f46
	incl	n
	pushl	u+4
	.data	
s1848:	.asciz	"E.O.Thorp does it again."
	.text	
	lea	s1848,%eax
	pushl	%eax
	pushl	$1
	call	pttrap109
	addl	$12,%esp
	pushl	u+4
	call	pttrap6
	addl	$4,%esp
	jmp	f47
f46:	movl	$207,n
	pushl	u+4
	.data	
s1903:	.asciz	" must have doctored the shuffle."
	.text	
	lea	s1903,%eax
	pushl	%eax
	pushl	%ebx
	pushl	%ecx
	pushl	%edx
	movl	%eax,%ebx
	pushl	%ebx
	lea	u+110,%eax
	pushl	%eax
	call	pttrap103
	addl	$8,%esp
	movl	%eax,%esi
	popl	%edx
	popl	%ecx
	popl	%ebx
	popl	%eax
	movl	%esi,%eax
	pushl	%eax
	pushl	$1
	call	pttrap109
	addl	$12,%esp
	pushl	u+4
	call	pttrap6
	addl	$4,%esp
f47:	jmp	f48
f45:	movl	$210,n
	pushl	u+4
	.data	
s1965:	.asciz	"Even shuffle."
	.text	
	lea	s1965,%eax
	pushl	%eax
	pushl	$1
	call	pttrap109
	addl	$12,%esp
	pushl	u+4
	call	pttrap6
	addl	$4,%esp
f48:f44:	movl	$213,n
	movl	u+14800,%eax
	movb	$0,(%eax)
f42:	leave	
	ret	
p2015:	pushl	%ebp
	movl	%esp, %ebp	
	movl	$220,n
	incl	u+84
	incl	n
	movl	u+84,%eax
	cmpl	$7,%eax
	jle	f49
	cmpl	$1,%eax
	jge	f50
	pushl	n
	call	pttrap13
f50:f49:	decl	%eax
	shl	$2,%eax
	lea	u+52,%ebx
	addl	%ebx,%eax
	pushl	%eax
	call	p350
	addl	$4,%esp
	movl	$222,n
	leave	
	ret	
p2049:	pushl	%ebp
	movl	%esp, %ebp	
	movl	$228,n
	incl	u+80
	incl	n
	movl	u+80,%eax
	cmpl	$7,%eax
	jle	f51
	cmpl	$1,%eax
	jge	f52
	pushl	n
	call	pttrap13
f52:f51:	decl	%eax
	shl	$2,%eax
	lea	u+16,%ebx
	addl	%ebx,%eax
	pushl	%eax
	call	p350
	addl	$4,%esp
	movl	$230,n
	leave	
	ret	
p2083:	pushl	%ebp
	movl	%esp, %ebp	
	movl	$238,n
	movb	$0,u+108
	incl	n
	movb	$0,u+109
	incl	n
	movl	$0,u+84
	incl	n
	movl	$0,u+80
	movl	$243,n
	call	p2015
	addl	$0,%esp
	movl	$244,n
	call	p2049
	addl	$0,%esp
	movl	$245,n
	call	p2015
	addl	$0,%esp
	movl	$246,n
	call	p2049
	addl	$0,%esp
	movl	$248,n
	pushl	u+84
	lea	u+44,%eax
	pushl	%eax
	lea	u+14808,%eax
	pushl	%eax
	call	p425
	addl	$12,%esp
	movl	$249,n
	pushl	u+4
	.data	
s2165:	.asciz	"The initial deal gives "
	.text	
	lea	s2165,%eax
	pushl	%eax
	pushl	$1
	call	pttrap109
	addl	$12,%esp
	pushl	u+4
	lea	u+110,%eax
	pushl	%eax
	pushl	$1
	call	pttrap109
	addl	$12,%esp
	pushl	u+4
	.data	
s2215:	.asciz	" :"
	.text	
	lea	s2215,%eax
	pushl	%eax
	pushl	$1
	call	pttrap109
	addl	$12,%esp
	pushl	u+4
	lea	u+14808,%eax
	pushl	%eax
	pushl	$1
	call	pttrap109
	addl	$12,%esp
	pushl	u+4
	call	pttrap6
	addl	$4,%esp
	incl	n
	pushl	u+80
	lea	u+8,%eax
	pushl	%eax
	lea	u+14808,%eax
	pushl	%eax
	call	p425
	addl	$12,%esp
	movl	$251,n
	pushl	u+4
	.data	
s2272:	.asciz	"  and the dealer :"
	.text	
	lea	s2272,%eax
	pushl	%eax
	pushl	$1
	call	pttrap109
	addl	$12,%esp
	pushl	u+4
	lea	u+14808,%eax
	pushl	%eax
	pushl	$1
	call	pttrap109
	addl	$12,%esp
	pushl	u+4
	.data	
s2317:	.asciz	"."
	.text	
	lea	s2317,%eax
	pushl	%eax
	pushl	$1
	call	pttrap109
	addl	$12,%esp
	pushl	u+4
	call	pttrap6
	addl	$4,%esp
	leave	
	ret	
p2339:	pushl	%ebp
	movl	%esp, %ebp	
	movl	8(%ebp),%eax
	movl	%eax,u+15844
	movl	12(%ebp),%eax
	movl	%eax,u+15840
	movl	16(%ebp),%eax
	movl	%eax,u+15836
	movl	20(%ebp),%eax
	movl	%eax,u+15832
	movl	$263,n
	movl	u+15844,%eax
	movl	$0,(%eax)
	incl	n
	movl	$0,u+15848
	movl	$266,n
	movl	$1,u+15852
b53:	movl	$267,n
	movl	u+15832,%eax
	cmpl	%eax,u+15852
	jg	f54
	movl	$269,n
	movl	u+15836,%eax
	movl	u+15852,%ebx
	cmpl	4(%eax),%ebx
	jle	f55
	cmpl	(%eax),%ebx
	jge	f56
	pushl	n
	call	pttrap13
f56:f55:	subl	(%eax),%ebx
	shl	$2,%ebx
	addl	$8,%eax
	addl	%eax,%ebx
	jmp	f57
v2407:	movl	$270,n
	movl	$272,n
	movl	u+15844,%eax
	movl	u+15844,%ebx
	movl	u+15836,%ecx
	movl	u+15852,%edx
	cmpl	4(%ecx),%edx
	jle	f58
	cmpl	(%ecx),%edx
	jge	f59
	pushl	n
	call	pttrap13
f59:f58:	subl	(%ecx),%edx
	shl	$2,%edx
	addl	$8,%ecx
	addl	%ecx,%edx
	movl	(%edx),%edx
	addl	(%ebx),%edx
	movl	%edx,(%eax)
	jmp	m2395
v2432:	movl	$273,n
	movl	$275,n
	movl	u+15844,%eax
	movl	u+15844,%ebx
	movl	$11,%ecx
	addl	(%ebx),%ecx
	movl	%ecx,(%eax)
	incl	n
	incl	u+15848
	jmp	m2395
a2395:b60:	movl	$279,n
	movl	$279,n
	movl	u+15844,%eax
	movl	u+15844,%ebx
	movl	$10,%ecx
	addl	(%ebx),%ecx
	movl	%ecx,(%eax)
	jmp	m2395
f57:	movl	(%ebx),%ebx
	decl	%ebx
	cmpl	$9,%ebx
	ja	b60
	shl	$2,%ebx
	movl	c2395(%ebx),%ebx
	jmp	*%ebx
	.data	
c2395:	.long	v2432
	.long	v2407
	.long	v2407
	.long	v2407
	.long	v2407
	.long	v2407
	.long	v2407
	.long	v2407
	.long	v2407
	.long	v2407
	.text	
m2395:	movl	$280,n
	movl	$282,n
	incl	u+15852
	jmp	b53
f54:b61:	movl	$285,n
	movl	u+15844,%eax
	cmpl	$21,(%eax)
	jle	f62
	cmpl	$0,u+15848
	je	f63
	incl	n
	movl	u+15844,%eax
	movl	u+15844,%ebx
	movl	(%ebx),%ebx
	subl	$10,%ebx
	movl	%ebx,(%eax)
	incl	n
	decl	u+15848
	jmp	b61
f63:f62:	movl	$290,n
	movl	u+15840,%eax
	cmpl	$0,u+15848
	jle	f64
	movb	$1,%bl
	jmp	f65
f64:	movb	$0,%bl
f65:	movb	%bl,(%eax)
	leave	
	ret	
p2580:	pushl	%ebp
	movl	%esp, %ebp	
	movl	$303,n
	pushl	u+80
	lea	u+8,%eax
	pushl	%eax
	lea	u+15856,%eax
	pushl	%eax
	lea	u+104,%eax
	pushl	%eax
	call	p2339
	addl	$16,%esp
	movl	$305,n
	cmpl	$21,u+104
	jle	f66
	incl	n
	pushl	u+4
	.data	
s2625:	.asciz	"Dealer goes bust."
	.text	
	lea	s2625,%eax
	pushl	%eax
	pushl	$1
	call	pttrap109
	addl	$12,%esp
	pushl	u+4
	call	pttrap6
	addl	$4,%esp
	incl	n
	movb	$1,u+109
	incl	n
	incl	u+92
	jmp	f67
f66:	movl	$309,n
	cmpl	$21,u+104
	jne	f68
	incl	n
	pushl	u+4
	.data	
s2699:	.asciz	"Dealer calls blackjack."
	.text	
	lea	s2699,%eax
	pushl	%eax
	pushl	$1
	call	pttrap109
	addl	$12,%esp
	pushl	u+4
	call	pttrap6
	addl	$4,%esp
	incl	n
	movb	$1,u+109
	incl	n
	incl	u+88
	jmp	f69
f68:	movl	$314,n
	movl	$17,%eax
	cmpl	u+104,%eax
	jle	f70
	incl	n
	call	p2049
	addl	$0,%esp
	movl	$316,n
	jmp	f71
f70:	movl	$317,n
	movb	$1,u+109
f71:	movl	$320,n
	cmpb	$0,u+109
	je	f72
	incl	n
	pushl	u+4
	.data	
s2809:	.asciz	"Dealer stands with "
	.text	
	lea	s2809,%eax
	pushl	%eax
	pushl	$1
	call	pttrap109
	addl	$12,%esp
	pushl	u+4
	pushl	u+104
	pushl	$1
	call	pttrap8
	addl	$12,%esp
	pushl	u+4
	.data	
s2855:	.asciz	"."
	.text	
	lea	s2855,%eax
	pushl	%eax
	pushl	$1
	call	pttrap109
	addl	$12,%esp
	pushl	u+4
	call	pttrap6
	addl	$4,%esp
	movl	$323,n
	movl	u+100,%eax
	cmpl	%eax,u+104
	jle	f73
	incl	n
	pushl	u+4
	.data	
s2892:	.asciz	"House wins."
	.text	
	lea	s2892,%eax
	pushl	%eax
	pushl	$1
	call	pttrap109
	addl	$12,%esp
	pushl	u+4
	call	pttrap6
	addl	$4,%esp
	incl	n
	incl	u+88
	jmp	f74
f73:	movl	$326,n
	movl	u+104,%eax
	cmpl	%eax,u+100
	jle	f75
	incl	n
	pushl	u+4
	.data	
s2956:	.asciz	" wins."
	.text	
	lea	s2956,%eax
	pushl	%eax
	pushl	%ebx
	pushl	%ecx
	pushl	%edx
	movl	%eax,%ebx
	pushl	%ebx
	lea	u+110,%eax
	pushl	%eax
	call	pttrap103
	addl	$8,%esp
	movl	%eax,%esi
	popl	%edx
	popl	%ecx
	popl	%ebx
	popl	%eax
	movl	%esi,%eax
	pushl	%eax
	pushl	$1
	call	pttrap109
	addl	$12,%esp
	pushl	u+4
	call	pttrap6
	addl	$4,%esp
	incl	n
	incl	u+92
	jmp	f76
f75:	movl	$330,n
	pushl	u+4
	.data	
s3003:	.asciz	"Tie game."
	.text	
	lea	s3003,%eax
	pushl	%eax
	pushl	$1
	call	pttrap109
	addl	$12,%esp
	pushl	u+4
	call	pttrap6
	addl	$4,%esp
f76:f74:	jmp	f77
f72:	movl	$333,n
	pushl	u+80
	lea	u+8,%eax
	pushl	%eax
	lea	u+15857,%eax
	pushl	%eax
	call	p425
	addl	$12,%esp
	movl	$334,n
	pushl	u+4
	.data	
s3059:	.asciz	"Dealer takes a card and now has "
	.text	
	lea	s3059,%eax
	pushl	%eax
	pushl	$1
	call	pttrap109
	addl	$12,%esp
	pushl	u+4
	lea	u+15857,%eax
	pushl	%eax
	pushl	$1
	call	pttrap109
	addl	$12,%esp
	pushl	u+4
	.data	
s3118:	.asciz	"."
	.text	
	lea	s3118,%eax
	pushl	%eax
	pushl	$1
	call	pttrap109
	addl	$12,%esp
	pushl	u+4
	call	pttrap6
	addl	$4,%esp
f77:f69:f67:	leave	
	ret	
p3147:	pushl	%ebp
	movl	%esp, %ebp	
	movl	$345,n
	movl	u+100,%eax
	cmpl	%eax,u+1136
	jle	f78
	incl	n
	call	p2015
	addl	$0,%esp
	movl	$347,n
	jmp	f79
f78:	movl	$348,n
	movb	$1,u+108
f79:	leave	
	ret	
p3187:	pushl	%ebp
	movl	%esp, %ebp	
	movb	8(%ebp),%al
	movb	%al,u+16881
	movl	$358,n
	movl	u+16,%eax
	movl	%eax,u+16884
	movl	$360,n
	cmpb	$0,u+16881
	je	f80
	movl	$362,n
	cmpl	$8,u+16884
	jle	f81
	movl	$364,n
	cmpl	$18,u+100
	jle	f82
	movb	$1,%al
	jmp	f83
f82:	movb	$0,%al
f83:	movb	%al,u+108
	jmp	f84
f81:	movl	$367,n
	cmpl	$17,u+100
	jle	f85
	movb	$1,%al
	jmp	f86
f85:	movb	$0,%al
f86:	movb	%al,u+108
f84:	jmp	f87
f80:	movl	$371,n
	cmpl	$1,u+16884
	jle	f88
	movl	$4,%eax
	cmpl	u+16884,%eax
	jle	f89
	movl	$373,n
	cmpl	$12,u+100
	jle	f90
	movb	$1,%al
	jmp	f91
f90:	movb	$0,%al
f91:	movb	%al,u+108
	jmp	f92
f89:f88:	movl	$374,n
	cmpl	$3,u+16884
	jle	f93
	movl	$7,%eax
	cmpl	u+16884,%eax
	jle	f94
	movl	$376,n
	cmpl	$11,u+100
	jle	f95
	movb	$1,%al
	jmp	f96
f95:	movb	$0,%al
f96:	movb	%al,u+108
	jmp	f97
f94:f93:	movl	$379,n
	cmpl	$16,u+100
	jle	f98
	movb	$1,%al
	jmp	f99
f98:	movb	$0,%al
f99:	movb	%al,u+108
f97:f92:f87:	movl	$383,n
	cmpb	$0,u+108
	jne	f100
	incl	n
	call	p2015
	addl	$0,%esp
	movl	$385,n
f100:	movl	$385,n
	leave	
	ret	
p3369:	pushl	%ebp
	movl	%esp, %ebp	
	movl	$396,n
	pushl	u+84
	lea	u+44,%eax
	pushl	%eax
	lea	u+16888,%eax
	pushl	%eax
	lea	u+100,%eax
	pushl	%eax
	call	p2339
	addl	$16,%esp
	movl	$398,n
	cmpl	$21,u+100
	jne	f101
	incl	n
	pushl	u+4
	.data	
s3417:	.asciz	" calls blackjack."
	.text	
	lea	s3417,%eax
	pushl	%eax
	pushl	%ebx
	pushl	%ecx
	pushl	%edx
	movl	%eax,%ebx
	pushl	%ebx
	lea	u+110,%eax
	pushl	%eax
	call	pttrap103
	addl	$8,%esp
	movl	%eax,%esi
	popl	%edx
	popl	%ecx
	popl	%ebx
	popl	%eax
	movl	%esi,%eax
	pushl	%eax
	pushl	$1
	call	pttrap109
	addl	$12,%esp
	pushl	u+4
	call	pttrap6
	addl	$4,%esp
	incl	n
	movb	$1,u+108
	incl	n
	movb	$1,u+109
	incl	n
	incl	u+92
	jmp	f102
f101:	movl	$403,n
	cmpl	$21,u+100
	jle	f103
	incl	n
	pushl	u+4
	.data	
s3503:	.asciz	" goes bust."
	.text	
	lea	s3503,%eax
	pushl	%eax
	pushl	%ebx
	pushl	%ecx
	pushl	%edx
	movl	%eax,%ebx
	pushl	%ebx
	lea	u+110,%eax
	pushl	%eax
	call	pttrap103
	addl	$8,%esp
	movl	%eax,%esi
	popl	%edx
	popl	%ecx
	popl	%ebx
	popl	%eax
	movl	%esi,%eax
	pushl	%eax
	pushl	$1
	call	pttrap109
	addl	$12,%esp
	pushl	u+4
	call	pttrap6
	addl	$4,%esp
	incl	n
	movb	$1,u+108
	incl	n
	movb	$1,u+109
	incl	n
	incl	u+88
	jmp	f104
f103:	movl	$409,n
	.data	
s3569:	.asciz	"E.O.Thorp"
	.text	
	lea	s3569,%eax
	pushl	%eax
	pushl	%ebx
	pushl	%ecx
	pushl	%edx
	movl	%eax,%ebx
	pushl	%ebx
	lea	u+110,%eax
	pushl	%eax
	call	pttrap107
	addl	$8,%esp
	movl	%eax,%esi
	popl	%edx
	popl	%ecx
	popl	%ebx
	popl	%eax
	movl	%esi,%eax
	cmpb	$0,%al
	je	f105
	incl	n
	movb	u+16888,%al
	pushl	%eax
	call	p3187
	addl	$4,%esp
	movl	$411,n
	jmp	f106
f105:	movl	$412,n
	call	p3147
	addl	$0,%esp
	movl	$413,n
f106:	movl	$415,n
	cmpb	$0,u+108
	je	f107
	incl	n
	pushl	u+4
	lea	u+110,%eax
	pushl	%eax
	pushl	$1
	call	pttrap109
	addl	$12,%esp
	pushl	u+4
	.data	
s3634:	.asciz	" stands with "
	.text	
	lea	s3634,%eax
	pushl	%eax
	pushl	$1
	call	pttrap109
	addl	$12,%esp
	pushl	u+4
	pushl	u+100
	pushl	$1
	call	pttrap8
	addl	$12,%esp
	pushl	u+4
	.data	
s3674:	.asciz	"."
	.text	
	lea	s3674,%eax
	pushl	%eax
	pushl	$1
	call	pttrap109
	addl	$12,%esp
	pushl	u+4
	call	pttrap6
	addl	$4,%esp
	jmp	f108
f107:	movl	$418,n
	pushl	u+84
	lea	u+44,%eax
	pushl	%eax
	lea	u+16889,%eax
	pushl	%eax
	call	p425
	addl	$12,%esp
	movl	$419,n
	pushl	u+4
	lea	u+110,%eax
	pushl	%eax
	pushl	$1
	call	pttrap109
	addl	$12,%esp
	pushl	u+4
	.data	
s3734:	.asciz	" takes a card and now has "
	.text	
	lea	s3734,%eax
	pushl	%eax
	pushl	$1
	call	pttrap109
	addl	$12,%esp
	pushl	u+4
	lea	u+16889,%eax
	pushl	%eax
	pushl	$1
	call	pttrap109
	addl	$12,%esp
	pushl	u+4
	.data	
s3787:	.asciz	"."
	.text	
	lea	s3787,%eax
	pushl	%eax
	pushl	$1
	call	pttrap109
	addl	$12,%esp
	pushl	u+4
	call	pttrap6
	addl	$4,%esp
f108:f104:f102:	leave	
	ret	
f30:	movl	$433,n
	pushl	u+4
	.data	
s3822:	.asciz	"This program simulates the game of blackjack."
	.text	
	lea	s3822,%eax
	pushl	%eax
	pushl	$1
	call	pttrap109
	addl	$12,%esp
	pushl	u+4
	call	pttrap6
	addl	$4,%esp
	incl	n
	pushl	u+4
	call	pttrap6
	addl	$4,%esp
	incl	n
	pushl	u+4
	.data	
s3900:	.asciz	"The dealer plays the compulsory strategy of standing on 17 or better."
	.text	
	lea	s3900,%eax
	pushl	%eax
	pushl	$1
	call	pttrap109
	addl	$12,%esp
	pushl	u+4
	call	pttrap6
	addl	$4,%esp
	incl	n
	pushl	u+4
	call	pttrap6
	addl	$4,%esp
	incl	n
	pushl	u+4
	.data	
s4002:	.asciz	"The player plays either"
	.text	
	lea	s4002,%eax
	pushl	%eax
	pushl	$1
	call	pttrap109
	addl	$12,%esp
	pushl	u+4
	call	pttrap6
	addl	$4,%esp
	incl	n
	pushl	u+4
	.data	
s4049:	.asciz	"  [1] The standard naive strategy of standing on n or better, or"
	.text	
	lea	s4049,%eax
	pushl	%eax
	pushl	$1
	call	pttrap109
	addl	$12,%esp
	pushl	u+4
	call	pttrap6
	addl	$4,%esp
	incl	n
	pushl	u+4
	.data	
s4137:	.asciz	"  [2] A simplified version of the strategy described by  E.O.Thorp"
	.text	
	lea	s4137,%eax
	pushl	%eax
	pushl	$1
	call	pttrap109
	addl	$12,%esp
	pushl	u+4
	call	pttrap6
	addl	$4,%esp
	incl	n
	pushl	u+4
	.data	
s4227:	.asciz	"      in his book 'Beat the Dealer' (Vintage Books, 1966) pp. 20-21."
	.text	
	lea	s4227,%eax
	pushl	%eax
	pushl	$1
	call	pttrap109
	addl	$12,%esp
	pushl	u+4
	call	pttrap6
	addl	$4,%esp
	incl	n
	pushl	u+4
	call	pttrap6
	addl	$4,%esp
	incl	n
	pushl	u+4
	.data	
s4328:	.asciz	"Input :"
	.text	
	lea	s4328,%eax
	pushl	%eax
	pushl	$1
	call	pttrap109
	addl	$12,%esp
	pushl	u+4
	call	pttrap6
	addl	$4,%esp
	incl	n
	pushl	u+4
	.data	
s4359:	.asciz	"  For each shuffle, a player name (character string of <= 20 characters),"
	.text	
	lea	s4359,%eax
	pushl	%eax
	pushl	$1
	call	pttrap109
	addl	$12,%esp
	pushl	u+4
	call	pttrap6
	addl	$4,%esp
	incl	n
	pushl	u+4
	.data	
s4456:	.asciz	"  and if the player name specified is not 'E.O.Thorp', the count [n]"
	.text	
	lea	s4456,%eax
	pushl	%eax
	pushl	$1
	call	pttrap109
	addl	$12,%esp
	pushl	u+4
	call	pttrap6
	addl	$4,%esp
	incl	n
	pushl	u+4
	.data	
s4548:	.asciz	"  on which the player stands."
	.text	
	lea	s4548,%eax
	pushl	%eax
	pushl	$1
	call	pttrap109
	addl	$12,%esp
	pushl	u+4
	call	pttrap6
	addl	$4,%esp
	incl	n
	pushl	u+4
	call	pttrap6
	addl	$4,%esp
	incl	n
	pushl	u+4
	.data	
s4610:	.asciz	"If the player name specified is 'E.O.Thorp', the player strategy used"
	.text	
	lea	s4610,%eax
	pushl	%eax
	pushl	$1
	call	pttrap109
	addl	$12,%esp
	pushl	u+4
	.data	
s4692:	.asciz	" will be Thorp's."
	.text	
	lea	s4692,%eax
	pushl	%eax
	pushl	$1
	call	pttrap109
	addl	$12,%esp
	incl	n
	pushl	u+4
	call	pttrap6
	addl	$4,%esp
	incl	n
	pushl	u+4
	.data	
s4735:	.asciz	"Otherwise, the player will use the standard stop on count > n strategy."
	.text	
	lea	s4735,%eax
	pushl	%eax
	pushl	$1
	call	pttrap109
	addl	$12,%esp
	pushl	u+4
	call	pttrap6
	addl	$4,%esp
	incl	n
	pushl	u+4
	call	pttrap6
	addl	$4,%esp
	incl	n
	pushl	u+4
	.data	
s4839:	.asciz	"The program will simulate one complete shuffle of play for each player."
	.text	
	lea	s4839,%eax
	pushl	%eax
	pushl	$1
	call	pttrap109
	addl	$12,%esp
	pushl	u+4
	call	pttrap6
	addl	$4,%esp
	movl	$454,n
	lea	u+17913,%eax
	pushl	%eax
	call	p691
	addl	$4,%esp
	movl	$456,n
b109:	movl	$456,n
	cmpb	$0,u+17913
	je	f110
	incl	n
	call	p151
	addl	$0,%esp
	movl	$458,n
	lea	u+17913,%eax
	pushl	%eax
	call	p1405
	addl	$4,%esp
	movl	$460,n
b111:	movl	$460,n
	cmpb	$0,u+17913
	je	f112
	incl	n
	call	p2083
	addl	$0,%esp
	movl	$463,n
b113:	movl	$463,n
	cmpb	$0,u+108
	jne	f114
	incl	n
	call	p3369
	addl	$0,%esp
	movl	$465,n
	jmp	b113
f114:b115:	movl	$467,n
	cmpb	$0,u+109
	jne	f116
	incl	n
	call	p2580
	addl	$0,%esp
	movl	$469,n
	jmp	b115
f116:	movl	$471,n
	lea	u+17913,%eax
	pushl	%eax
	call	p1405
	addl	$4,%esp
	movl	$472,n
	jmp	b111
f112:	movl	$474,n
	lea	u+17913,%eax
	pushl	%eax
	call	p691
	addl	$4,%esp
	movl	$475,n
	jmp	b109
f110:	movl	$477,n
	call	pttrap0
	leave	
	ret	
