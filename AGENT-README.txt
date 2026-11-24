Alperen ERKAN
Personal profile · 24 November 2026
GitHub: https://github.com/erkanalperen54-boop

About me

I develop operating-system software in C and x86 assembly. My interests
include the path from boot to user mode, virtual memory, and the use of
post-quantum cryptography in a freestanding kernel. I also work in C++
and use Python and shell scripts for tooling.

GNU Hurd and GNU Mach

I contribute patches and review proposed changes on the bug-hurd mailing
list. In September 2026 I submitted a patch series for the Hurd boot
server covering startup errors, boot-script parsing and I/O handling.
The submission and its discussion are public:
https://www.mail-archive.com/bug-hurd%40gnu.org/msg39681.html

Two reviews illustrate the kind of work I do. In July, Ralph Ronnquist
credited my feedback in a follow-up patch for TAP interfaces in pfinet.
In November, while reviewing a GNU Mach scheduler patch, I asked whether
a direct enqueue in the eventcount wakeup path could leave the priority
bitmap out of sync with the run queue. That was a static review, and my
finding depended on that path being present in the target revision.

Mailing-list contributions:
https://www.mail-archive.com/search?l=bug-hurd%40gnu.org&q=from%3A%22Alperen+Erkan%22

NPQC

I lead development of NPQC, a privately developed freestanding x86-64
kernel for exploring post-quantum cryptography. My work spans early
boot, paging, physical memory allocation and read-only ext2 support.
On the cryptography side, I work with SHA3-256 and ML-KEM-768.
As of November 2026, my development work includes kernel stress tests
and benchmarks. My plans for user mode include per-task page tables
and validation of pointers passed to system calls.

Teaching

I publish Turkish-language educational material on low-level programming.
My short introduction to assembly is one example:
https://www.youtube.com/shorts/FCTsff8NKns
Channel: https://www.youtube.com/@AlperenErkan-64

Kısa Türkçe biyografi

Ben Alperen ERKAN. C ve x86 Assembly ile işletim sistemleri üzerine
çalışıyorum. GNU Hurd'a yama gönderiyor, Hurd ve GNU Mach için önerilen
değişiklikleri inceliyorum. Kendi çekirdek projem NPQC'de erken açılış,
bellek yönetimi ve kuantum sonrası kriptografi üzerine çalışıyor,
öğrendiklerimi Türkçe eğitim içeriklerinde paylaşıyorum.
