# $FreeBSD: head/lib/libnv/tests/Makefile 289172 2015-10-12 08:16:03Z ngie $

ATF_TESTS_C= \
	nvlist_send_recv_test

ATF_TESTS_CXX=	\
	dnv_tests \
	nv_array_tests \
	nv_tests

TAP_TESTS_C+=	nvlist_add_test
TAP_TESTS_C+=	nvlist_exists_test
TAP_TESTS_C+=	nvlist_free_test
TAP_TESTS_C+=	nvlist_get_test
TAP_TESTS_C+=	nvlist_move_test

LIBADD+=	nv

WARNS?=		3

.include <bsd.test.mk>
