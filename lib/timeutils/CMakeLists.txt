set(TIMEUTILS_HEADERS
    timeutils/cache.h
    timeutils/conv.h
    timeutils/scan-timestamp.h
    timeutils/format.h
    timeutils/misc.h
    timeutils/names.h
    timeutils/unixtime.h
    timeutils/zoneinfo.h
    timeutils/wallclocktime.h
    PARENT_SCOPE)

set(TIMEUTILS_SOURCES
    timeutils/cache.c
    timeutils/conv.c
    timeutils/scan-timestamp.c
    timeutils/format.c
    timeutils/misc.c
    timeutils/names.c
    timeutils/unixtime.c
    timeutils/zoneinfo.c
    timeutils/wallclocktime.c
    PARENT_SCOPE)

add_test_subdirectory(tests)
