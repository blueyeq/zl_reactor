# tests case
MAINTAINERCLEANFILES   = Makefile.in

if ZL_TEST_SUITES
SUBDIRS = base thread net
endif

# lib case 

CXXFLAGS =-Wall -Werror -g -O2 -fPIC -Wno-unused-function

#plugindir = ../../lib
plugindir = ${exec_prefix}/lib

plugin_LTLIBRARIES = libzlreactor.la

## 安装根目录

## 安装库目录

## 安装头文件目录

libzlreactor_la_LIBFLAGS =
libzlreactor_la_LIBADD =

INCLUDES                   = -I../
libzlreactor_la_CPPFLAGS   = -O2 -std=c++0x -fPIC -shared
libzlreactor_la_LDFLAGS    = -lrt -version-info 1:0:1	

libzlreactor_la_SOURCES =                             \
					 base/Date.cpp                    \
					 base/DateTimeUtil.cpp            \
					 base/File.cpp                    \
					 base/FileUtil.cpp                \
					 base/Timestamp.cpp               \
					 base/Demangle.cpp                \
					 base/Exception.cpp               \
					 base/Daemonize.cpp               \
					 base/StringUtil.cpp              \
					 base/StringPiece.cpp             \
					 base/MasterWorkerProcess.cpp     \
					 base/ProcessUtil.cpp             \
					 base/Logger.cpp                  \
					 base/LogFile.cpp                 \
					 base/AsyncLogger.cpp             \
					 utility/StringHash.cpp           \
					 utility/Base64.cpp               \
					 utility/Md5.cpp                  \
					 utility/SHA1.cpp                  \
					 thread/Thread.cpp                \
					 thread/ThreadGroup.cpp           \
					 thread/ThreadPool.cpp            \
					 net/poller/Poller.cpp            \
					 net/poller/SelectPoller.cpp      \
					 net/poller/PollPoller.cpp        \
					 net/poller/EpollPoller.cpp       \
					 net/NetUtil.cpp                  \
					 net/ByteBuffer.cpp               \
					 net/SocketUtil.cpp               \
					 net/InetAddress.cpp              \
					 net/DomainResolver.cpp           \
					 net/Socket.cpp                   \
					 net/EventLoop.cpp                \
					 net/EventLoopThreadPool.cpp      \
					 net/Channel.cpp                  \
					 net/TcpAcceptor.cpp              \
					 net/TcpConnection.cpp            \
					 net/TcpServer.cpp                \
					 net/TcpClient.cpp                \
					 net/TcpConnector.cpp             \
					 net/TimerQueue.cpp               \
					 net/Eventfd.cpp                  \
					 net/Timerfd.cpp                  \
					 net/Signalfd.cpp                 \
					 net/http/HttpKeyValue.cpp        \
					 net/http/UriQueryParams.cpp      \
					 net/http/UriUtil.cpp             \
					 net/http/HttpRequest.cpp         \
					 net/http/HttpResponse.cpp        \
					 net/http/HttpContext.cpp         \
					 net/http/HttpServer.cpp          \
					 net/websocket/WebSocket.cpp      \
					 net/websocket/WebSocketServer.cpp

