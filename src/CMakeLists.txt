cmake_minimum_required(VERSION 2.8)

set (SAGTM_IFACE
    thread.h
    )

set (SAGTM_H
    ${SAGTM_IFACE}
    )

set (SAGTM_C
    thread.c
    )

add_library (sagtm SHARED ${SAGTM_C})
add_library (sagtm_st STATIC ${SAGTM_C})

