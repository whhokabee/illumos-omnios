#
# This file and its contents are supplied under the terms of the
# Common Development and Distribution License ("CDDL"), version 1.0.
# You may only use this file in accordance with the terms of version
# 1.0 of the CDDL.
#
# A full copy of the text of the CDDL should have accompanied this
# source.  A copy of the CDDL is also available via the Internet
# at http://www.illumos.org/license/CDDL.
#

#
# Copyright 2011, Richard Lowe
# Copyright 2018 Nexenta Systems, Inc.
# Copyright 2013, OmniTI Computer Consulting, Inc. All rights reserved.
# Copyright 2014 Garrett D'Amore <garrett@damore.org>
# Copyright 2020 Joyent, Inc.
# Copyright 2018 Jason King
# Copyright 2022 OmniOS Community Edition (OmniOSce) Association.
# Copyright 2025 Hans Rosenfeld
#

include		$(SRC)/Makefile.master

MANSECT=	3c

MANFILES=	__fbufsize.3c					\
		_longjmp.3c					\
		_stack_grow.3c					\
		a64l.3c						\
		abort.3c					\
		abs.3c						\
		addsev.3c					\
		addseverity.3c					\
		aio_cancel.3c					\
		aio_error.3c					\
		aio_fsync.3c					\
		aio_read.3c					\
		aio_return.3c					\
		aio_suspend.3c					\
		aio_waitn.3c					\
		aio_write.3c					\
		aiocancel.3c					\
		aioread.3c					\
		aiowait.3c					\
		aligned_alloc.3c				\
		arc4random.3c					\
		assert.3c					\
		atexit.3c					\
		atomic_add.3c					\
		atomic_and.3c					\
		atomic_bits.3c					\
		atomic_cas.3c					\
		atomic_dec.3c					\
		atomic_inc.3c					\
		atomic_ops.3c					\
		atomic_or.3c					\
		atomic_swap.3c					\
		attropen.3c					\
		basename.3c					\
		bsd_signal.3c					\
		bsearch.3c					\
		bstring.3c					\
		btowc.3c					\
		byteorder.3c					\
		c16rtomb.3c					\
		call_once.3c					\
		catgets.3c					\
		catopen.3c					\
		cfgetispeed.3c					\
		cfsetispeed.3c					\
		clearenv.3c					\
		clock.3c					\
		clock_nanosleep.3c				\
		clock_settime.3c				\
		closedir.3c					\
		closefrom.3c					\
		cnd.3c						\
		cond_init.3c					\
		confstr.3c					\
		crypt.3c					\
		crypt_genhash_impl.3c				\
		crypt_gensalt.3c				\
		crypt_gensalt_impl.3c				\
		cset.3c						\
		ctermid.3c					\
		ctime.3c					\
		ctype.3c					\
		cuserid.3c					\
		daemon.3c					\
		decimal_to_floating.3c				\
		difftime.3c					\
		directio.3c					\
		dirfd.3c					\
		dirname.3c					\
		div.3c						\
		dladdr.3c					\
		dlclose.3c					\
		dldump.3c					\
		dlerror.3c					\
		dlinfo.3c					\
		dlopen.3c					\
		dlsym.3c					\
		door_bind.3c					\
		door_call.3c					\
		door_create.3c					\
		door_cred.3c					\
		door_getparam.3c				\
		door_info.3c					\
		door_return.3c					\
		door_revoke.3c					\
		door_server_create.3c				\
		door_ucred.3c					\
		drand48.3c					\
		dup2.3c						\
		econvert.3c					\
		ecvt.3c						\
		enable_extended_FILE_stdio.3c			\
		encrypt.3c					\
		end.3c						\
		endian.3c					\
		epoll_create.3c					\
		epoll_ctl.3c					\
		epoll_wait.3c					\
		err.3c						\
		euclen.3c					\
		eventfd.3c					\
		exit.3c						\
		fattach.3c					\
		fclose.3c					\
		fcloseall.3c					\
		fdatasync.3c					\
		fdclose.3c					\
		fdetach.3c					\
		fdopen.3c					\
		ferror.3c					\
		fflush.3c					\
		ffs.3c						\
		fgetattr.3c					\
		fgetc.3c					\
		fgetpos.3c					\
		fgetwc.3c					\
		floating_to_decimal.3c				\
		flock.3c					\
		flockfile.3c					\
		fmemopen.3c					\
		fmtmsg.3c					\
		fnmatch.3c					\
		fopen.3c					\
		fpgetround.3c					\
		fputc.3c					\
		fputwc.3c					\
		fputws.3c					\
		fread.3c					\
		freopen.3c					\
		fseek.3c					\
		fsetpos.3c					\
		fsync.3c					\
		ftell.3c					\
		ftime.3c					\
		ftok.3c						\
		fts.3c						\
		ftw.3c						\
		fwide.3c					\
		fwprintf.3c					\
		fwrite.3c					\
		fwscanf.3c					\
		get_nprocs.3c					\
		getcpuid.3c					\
		getcwd.3c					\
		getdate.3c					\
		getdtablesize.3c				\
		getentropy.3c					\
		getenv.3c					\
		getexecname.3c					\
		getgrnam.3c					\
		getgrouplist.3c					\
		gethostid.3c					\
		gethostname.3c					\
		gethrtime.3c					\
		getline.3c					\
		getloadavg.3c					\
		getlocalename_l.3c				\
		getlogin.3c					\
		getmntent.3c					\
		getnetgrent.3c					\
		getopt.3c					\
		getopt_long.3c					\
		getpagesize.3c					\
		getpagesizes.3c					\
		getpass.3c					\
		getpeerucred.3c					\
		getpriority.3c					\
		getprogname.3c					\
		getpw.3c					\
		getpwnam.3c					\
		getrusage.3c					\
		gets.3c						\
		getspnam.3c					\
		getsubopt.3c					\
		gettext.3c					\
		gettimeofday.3c					\
		gettxt.3c					\
		getusershell.3c					\
		getutent.3c					\
		getutxent.3c					\
		getvfsent.3c					\
		getwc.3c					\
		getwchar.3c					\
		getwd.3c					\
		getwidth.3c					\
		getws.3c					\
		getzoneid.3c					\
		glob.3c						\
		grantpt.3c					\
		hsearch.3c					\
		iconv.3c					\
		iconv_close.3c					\
		iconv_open.3c					\
		imaxabs.3c					\
		imaxdiv.3c					\
		index.3c					\
		inet.3c						\
		initgroups.3c					\
		inotify_init.3c					\
		inotify_add_watch.3c				\
		inotify_rm_watch.3c				\
		insque.3c					\
		is_system_labeled.3c				\
		isaexec.3c					\
		isastream.3c					\
		isatty.3c					\
		isnand.3c					\
		iswalpha.3c					\
		iswctype.3c					\
		killpg.3c					\
		lckpwdf.3c					\
		lfmt.3c						\
		lio_listio.3c					\
		localeconv.3c					\
		lockf.3c					\
		lsearch.3c					\
		madvise.3c					\
		makecontext.3c					\
		makedev.3c					\
		malloc.3c					\
		mblen.3c					\
		mbrlen.3c					\
		mbrtoc16.3c					\
		mbsinit.3c					\
		mbsrtowcs.3c					\
		mbstowcs.3c					\
		mbtowc.3c					\
		membar_ops.3c					\
		memory.3c					\
		memset_s.3c					\
		mkfifo.3c					\
		mkstemp.3c					\
		mktemp.3c					\
		mktime.3c					\
		mlock.3c					\
		mlockall.3c					\
		monitor.3c					\
		mq_close.3c					\
		mq_getattr.3c					\
		mq_notify.3c					\
		mq_open.3c					\
		mq_receive.3c					\
		mq_send.3c					\
		mq_setattr.3c					\
		mq_unlink.3c					\
		msync.3c					\
		mtx.3c						\
		mutex_init.3c					\
		nanosleep.3c					\
		ndbm.3c						\
		newlocale.3c					\
		nl_langinfo.3c					\
		offsetof.3c					\
		open_memstream.3c				\
		opendir.3c					\
		perror.3c					\
		pfmt.3c						\
		plock.3c					\
		popen.3c					\
		port_alert.3c					\
		port_associate.3c				\
		port_create.3c					\
		port_get.3c					\
		port_send.3c					\
		posix_fadvise.3c				\
		posix_fallocate.3c				\
		posix_madvise.3c				\
		posix_memalign.3c				\
		posix_openpt.3c					\
		posix_spawn.3c					\
		posix_spawn_file_actions_addchdir.3c		\
		posix_spawn_file_actions_addclose.3c		\
		posix_spawn_file_actions_addclosefrom_np.3c	\
		posix_spawn_file_actions_adddup2.3c		\
		posix_spawn_file_actions_destroy.3c		\
		posix_spawn_pipe_np.3c				\
		posix_spawnattr_destroy.3c			\
		posix_spawnattr_getflags.3c			\
		posix_spawnattr_getpgroup.3c			\
		posix_spawnattr_getschedparam.3c		\
		posix_spawnattr_getschedpolicy.3c		\
		posix_spawnattr_getsigdefault.3c		\
		posix_spawnattr_getsigignore_np.3c		\
		posix_spawnattr_getsigmask.3c			\
		printf.3c					\
		priv_addset.3c					\
		priv_set.3c					\
		priv_str_to_set.3c				\
		pset_getloadavg.3c				\
		psignal.3c					\
		pthread_atfork.3c				\
		pthread_attr_get_np.3c				\
		pthread_attr_getdetachstate.3c			\
		pthread_attr_getguardsize.3c			\
		pthread_attr_getinheritsched.3c			\
		pthread_attr_getname_np.3c			\
		pthread_attr_getschedparam.3c			\
		pthread_attr_getschedpolicy.3c			\
		pthread_attr_getscope.3c			\
		pthread_attr_getstack.3c			\
		pthread_attr_getstackaddr.3c			\
		pthread_attr_getstacksize.3c			\
		pthread_attr_init.3c				\
		pthread_barrier_destroy.3c			\
		pthread_barrier_wait.3c				\
		pthread_barrierattr_destroy.3c			\
		pthread_barrierattr_getpshared.3c		\
		pthread_cancel.3c				\
		pthread_cleanup_pop.3c				\
		pthread_cleanup_push.3c				\
		pthread_cond_init.3c				\
		pthread_cond_signal.3c				\
		pthread_cond_wait.3c				\
		pthread_condattr_getclock.3c			\
		pthread_condattr_getpshared.3c			\
		pthread_condattr_init.3c			\
		pthread_create.3c				\
		pthread_detach.3c				\
		pthread_equal.3c				\
		pthread_exit.3c					\
		pthread_getconcurrency.3c			\
		pthread_getname_np.3c				\
		pthread_getschedparam.3c			\
		pthread_getspecific.3c				\
		pthread_join.3c					\
		pthread_key_create.3c				\
		pthread_key_delete.3c				\
		pthread_kill.3c					\
		pthread_mutex_consistent.3c			\
		pthread_mutex_getprioceiling.3c			\
		pthread_mutex_init.3c				\
		pthread_mutex_lock.3c				\
		pthread_mutex_timedlock.3c			\
		pthread_mutexattr_getprioceiling.3c		\
		pthread_mutexattr_getprotocol.3c		\
		pthread_mutexattr_getpshared.3c			\
		pthread_mutexattr_getrobust.3c			\
		pthread_mutexattr_gettype.3c			\
		pthread_mutexattr_init.3c			\
		pthread_once.3c					\
		pthread_rwlock_init.3c				\
		pthread_rwlock_rdlock.3c			\
		pthread_rwlock_timedrdlock.3c			\
		pthread_rwlock_timedwrlock.3c			\
		pthread_rwlock_unlock.3c			\
		pthread_rwlock_wrlock.3c			\
		pthread_rwlockattr_getpshared.3c		\
		pthread_rwlockattr_init.3c			\
		pthread_self.3c					\
		pthread_setcancelstate.3c			\
		pthread_setcanceltype.3c			\
		pthread_setschedprio.3c				\
		pthread_sigmask.3c				\
		pthread_spin_destroy.3c				\
		pthread_spin_lock.3c				\
		pthread_spin_unlock.3c				\
		pthread_testcancel.3c				\
		ptrace.3c					\
		ptsname.3c					\
		putenv.3c					\
		putpwent.3c					\
		puts.3c						\
		putspent.3c					\
		putws.3c					\
		qsort.3c					\
		quick_exit.3c					\
		raise.3c					\
		rand.3c						\
		random.3c					\
		rctl_walk.3c					\
		rctlblk_set_value.3c				\
		re_comp.3c					\
		readdir.3c					\
		realpath.3c					\
		reboot.3c					\
		regcmp.3c					\
		regcomp.3c					\
		remove.3c					\
		rewind.3c					\
		rewinddir.3c					\
		rwlock.3c					\
		scandir.3c					\
		scanf.3c					\
		sched_get_priority_max.3c			\
		sched_getparam.3c				\
		sched_getscheduler.3c				\
		sched_rr_get_interval.3c			\
		sched_setparam.3c				\
		sched_setscheduler.3c				\
		sched_yield.3c					\
		schedctl_init.3c				\
		seekdir.3c					\
		select.3c					\
		sem_close.3c					\
		sem_destroy.3c					\
		sem_getvalue.3c					\
		sem_init.3c					\
		sem_open.3c					\
		sem_post.3c					\
		sem_timedwait.3c				\
		sem_unlink.3c					\
		sem_wait.3c					\
		semaphore.3c					\
		set_constraint_handler_s.3c			\
		setbuf.3c					\
		setbuffer.3c					\
		setcat.3c					\
		setenv.3c					\
		setjmp.3c					\
		setkey.3c					\
		setlabel.3c					\
		setlocale.3c					\
		shm_open.3c					\
		shm_unlink.3c					\
		sigfpe.3c					\
		siginterrupt.3c					\
		signal.3c					\
		signalfd.3c					\
		sigqueue.3c					\
		sigsetops.3c					\
		sigstack.3c					\
		sigwaitinfo.3c					\
		sleep.3c					\
		smt_pause.3c					\
		ssignal.3c					\
		stack_getbounds.3c				\
		stack_inbounds.3c				\
		stack_setbounds.3c				\
		stack_violation.3c				\
		stdc_bit_ceil.3c				\
		stdc_bit_floor.3c				\
		stdc_bit_width.3c				\
		stdc_count_ones.3c				\
		stdc_count_zeros.3c				\
		stdc_first_leading_one.3c			\
		stdc_first_leading_zero.3c			\
		stdc_first_trailing_one.3c			\
		stdc_first_trailing_zero.3c			\
		stdc_has_single_bit.3c				\
		stdc_leading_ones.3c				\
		stdc_leading_zeros.3c				\
		stdc_trailing_ones.3c				\
		stdc_trailing_zeros.3c				\
		stdio.3c					\
		str2sig.3c					\
		strcoll.3c					\
		strerror.3c					\
		strfmon.3c					\
		strftime.3c					\
		string.3c					\
		string_to_decimal.3c				\
		strptime.3c					\
		strsignal.3c					\
		strtod.3c					\
		strtoimax.3c					\
		strtol.3c					\
		strtonum.3c					\
		strtoul.3c					\
		strtows.3c					\
		strxfrm.3c					\
		swab.3c						\
		sync_instruction_memory.3c			\
		syncfs.3c					\
		sysconf.3c					\
		syslog.3c					\
		system.3c					\
		tcdrain.3c					\
		tcflow.3c					\
		tcflush.3c					\
		tcgetattr.3c					\
		tcgetpgrp.3c					\
		tcgetsid.3c					\
		tcsendbreak.3c					\
		tcsetattr.3c					\
		tcsetpgrp.3c					\
		tell.3c						\
		telldir.3c					\
		termios.3c					\
		thr_create.3c					\
		thr_exit.3c					\
		thr_getname.3c					\
		thr_getconcurrency.3c				\
		thr_getprio.3c					\
		thr_join.3c					\
		thr_keycreate.3c				\
		thr_kill.3c					\
		thr_main.3c					\
		thr_min_stack.3c				\
		thr_self.3c					\
		thr_sigsetmask.3c				\
		thr_stksegment.3c				\
		thr_suspend.3c					\
		thr_yield.3c					\
		thrd_create.3c					\
		thrd_current.3c					\
		thrd_detach.3c					\
		thrd_equal.3c					\
		thrd_exit.3c					\
		thrd_join.3c					\
		thrd_yield.3c					\
		timer_create.3c					\
		timer_delete.3c					\
		timer_settime.3c				\
		timeradd.3c					\
		timerfd_create.3c				\
		timespec_get.3c					\
		tmpfile.3c					\
		tmpnam.3c					\
		toascii.3c					\
		tolower.3c					\
		toupper.3c					\
		towlower.3c					\
		towupper.3c					\
		truncate.3c					\
		tsearch.3c					\
		tss.3c						\
		ttyname.3c					\
		ttyslot.3c					\
		u8_strcmp.3c					\
		u8_textprep_str.3c				\
		u8_validate.3c					\
		ualarm.3c					\
		uconv_u16tou32.3c				\
		ucontext_alloc.3c				\
		ucred.3c					\
		ungetc.3c					\
		ungetwc.3c					\
		unlockpt.3c					\
		unsetenv.3c					\
		uselocale.3c					\
		usleep.3c					\
		vfwprintf.3c					\
		vlfmt.3c					\
		vpfmt.3c					\
		vprintf.3c					\
		vsyslog.3c					\
		wait.3c						\
		wait3.3c					\
		waitpid.3c					\
		walkcontext.3c					\
		wcpcpy.3c					\
		wcscasecmp.3c					\
		wcscoll.3c					\
		wcsdup.3c					\
		wcsftime.3c					\
		wcslcat.3c					\
		wcslcpy.3c					\
		wcslen.3c					\
		wcsrtombs.3c					\
		wcsstr.3c					\
		wcstod.3c					\
		wcstoimax.3c					\
		wcstol.3c					\
		wcstombs.3c					\
		wcstoul.3c					\
		wcstring.3c					\
		wcswidth.3c					\
		wcsxfrm.3c					\
		wctob.3c					\
		wctomb.3c					\
		wctrans.3c					\
		wctype.3c					\
		wcwidth.3c					\
		wmemchr.3c					\
		wmemcmp.3c					\
		wmemcpy.3c					\
		wmemmove.3c					\
		wmemset.3c					\
		wordexp.3c					\
		wsprintf.3c					\
		wsscanf.3c					\
		wstring.3c

.KEEP_STATE:

include		$(SRC)/man/Makefile.man

install:	$(ROOTMANFILES) $(MANLINK_SRCS)
	$(MANLINK_INSTALL)
