# $FreeBSD$

TESTSDIR=	${TESTSBASE}/sys/kern

ATF_TESTS_C=	unix_seqpacket_test
TEST_METADATA.unix_seqpacket_test+=	timeout="15"

LDADD.unix_seqpacket_test+=		-lpthread

WARNS?=	5

.include <bsd.test.mk>
