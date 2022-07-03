<h2 align="center">eBPF</h2>

## Websites:

- https://confused.ai/
- https://ebpf.io/
- eBPF Mailing List: http://vger.kernel.org/vger-lists.html#bpf
- See all the ebpf patches together: https://patchwork.kernel.org/project/netdevbpf/list/
- https://vbpf.github.io/
- https://bpfdeploy.io/
- https://foniod.org/

## Blogs and articles:

- https://blog.redsift.com/labs/writing-bpf-code-in-rust/
- https://jvns.ca/blog/2018/02/05/rust-bcc/
- http://terenceli.github.io/%E6%8A%80%E6%9C%AF/2020/01/18/ebpf-in-c
- https://sysdig.com/blog/the-art-of-writing-ebpf-programs-a-primer/
- http://unhandledexpression.com/general/rust/2018/02/02/poc-compiling-to-ebpf-from-rust.html
- https://bolinfest.github.io/opensnoop-native/
- https://docs.cilium.io/en/latest/bpf/
- https://www.iovisor.org/technology/xdp
- https://www.kernel.org/doc/Documentation/kprobes.txt
- https://www.trailofbits.com/post/all-your-tracing-are-belong-to-bpf
- https://www.isovalent.com/blog/post/2021-08-ebpf-foundation-announcement
- https://cloudblogs.microsoft.com/opensource/2021/05/10/making-ebpf-work-on-windows/
- https://blog.px.dev/cpu-profiling-3/
- https://docs.cilium.io/en/stable/intro/#functionality-overview
- https://itnext.io/epbf-understanding-the-next-gen-networking-security-observability-for-cloud-native-workloads-1fe8ad87ee0f
- https://docs.cilium.io/en/latest/bpf/
- https://www.iovisor.org/technology/xdp
- https://medium.com/thermokline/confused-by-ebpf-9d4a8bce318e
- https://medium.com/zendesk-engineering/hunting-down-a-c-memory-leak-in-a-go-program-2d08b24b617d
- https://medium.com/zendesk-engineering/hunting-down-a-c-memory-leak-in-a-go-program-2d08b24b617d
- https://kentiklabs.com/blog/container-visibility/
- https://medium.com/nttlabs/bpf-and-async-rust-c1818f03aff7
- https://lists.llvm.org/pipermail/cfe-dev/2021-December/069635.html
- https://itnext.io/epbf-understanding-the-next-gen-networking-security-observability-for-cloud-native-workloads-1fe8ad87ee0f
- https://www.infoq.com/news/2022/01/ebpf-wasm-service-mesh/
- https://ish-ar.io/ebpf-dive-into-the-verifier/
- https://ish-ar.io/ebpf-my-first-2-days-with-it/
- https://ish-ar.io/kprobes-in-a-nutshell/
- Good ref guide: BPF CO-RE(Code Once - Run Everywhere) reference guide: https://nakryiko.com/posts/bpf-core-reference-guide/
- https://www.infoq.com/podcasts/liz-rice-ebpf/
- BPF Type Format: https://www.kernel.org/doc/html/latest/bpf/btf.html
- A memory allocator for BPF code: https://lwn.net/Articles/883454/
- Fuzzing for eBPF JIT bugs in the Linux kernel: https://scannell.io/posts/ebpf-fuzzing/
- https://research.nccgroup.com/2021/08/06/some-musings-on-common-ebpf-linux-tracing-bugs/
- https://taras.glek.net/post/ebpf-mmap-page-fault-tracing/
- bpf: Populate bpffs with map and prog iterators: https://lwn.net/Articles/826389/
- Lifetime Of BPF objects: https://facebookmicrosites.github.io/bpf/blog/2018/08/31/object-lifetime.html
- Dive into BPF: a list of reading material: https://qmonnet.github.io/whirl-offload/2016/09/01/dive-into-bpf/
- A thorough introduction to eBPF: https://lwn.net/Articles/740157/
- BPF: the universal in-kernel virtual machine: https://lwn.net/Articles/599755/
- BPF: In kernel virtual machine: https://www.slideshare.net/AlexeiStarovoitov/bpf-inkernel-virtual-machine
- https://www.seekret.io/blog/handling-the-challenge-of-deploying-ebpf-into-the-wild/
- Every Boring Problem Found in eBPF: https://tmpout.sh/2/4.html
- eBPF Kernel Image Lockdown and eBPF Flexibility: https://djalal.opendz.org/post/ebpf-kernel-image-lockdown-and-ebpf-flexibility/
- eBPF nuances on Minikube: https://www.seekret.io/blog/ebpf-nuances-on-minikube/
- BPF Compiler Collection Tools (BCC Tools) | Ultimate Guide: https://www.containiq.com/post/bcc-tools
- Intro to BPF CO-RE: https://layalina.io/2022/04/23/intro-to-bpf-co-re.html
- https://nakryiko.com/posts/libbpf-bootstrap/
- http://vger.kernel.org/bpfconf2022.html
- Overview of eBPF procfs kernel parameters: https://www.mdaverde.com/posts/ebpf-procfs-settings/
- When eBPF meets TLS: https://github.com/quarkslab/conf-presentations/blob/master/CanSecWest-2022/When%20eBPF%20meets%20TLS.pdf
- https://www.scylladb.com/2020/05/05/how-io_uring-and-ebpf-will-revolutionize-programming-in-linux/
- https://buoyant.io/2022/06/07/ebpf-sidecars-and-the-future-of-the-service-mesh/
- https://bmiguel-teixeira.medium.com/tracing-tls-traffic-ebpf-style-b588523133ab
- https://www.grant.pizza/blog/bpf-concurrency/
- Introduction to eBPF: https://blog.sofiane.cc/eBPFintroduction/

### Tutorials:

- https://coroot.com/blog/building-a-service-map-using-ebpf

## Dev:

- BPF kernel dev process, submitting patches and QA: https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/tree/Documentation/bpf/bpf_devel_QA.rst
- BPF API docs: https://github.com/iovisor/bpf-docs/blob/master/bpf_helpers.rst
- BPF Office Hours: https://docs.google.com/spreadsheets/d/1LfrDXZ9-fdhvPEp_LHkxAMYyxxpwBXjywWa0AejEveU/edit#gid=0

## Blog series/Article collection:

- https://nakryiko.com/categories/bpf/
- https://www.ferrisellis.com/tags/ebpf/
- https://facebookmicrosites.github.io/bpf/blog/
- https://blog.cloudflare.com/tag/ebpf/
- https://www.iovisor.org/resources/blog

## Books:

- eBPF Book: http://www.brendangregg.com/bpf-performance-tools-book.html
- https://isovalent.com/data/liz-rice-what-is-ebpf.pdf

## Repos:

- eBPF github org: https://github.com/ebpf-io
- https://github.com/zoidbergwill/awesome-ebpf
- Tools for BPF-based Linux IO analysis, networking, monitoring, and more : https://github.com/iovisor/bcc
- Automated upstream mirror for libbpf stand-alone build : https://github.com/libbpf/libbpf
- https://github.com/alessandrod/bpf-linker
- https://github.com/alessandrod/snuffy/blob/master/src/main.rs
- https://github.com/jvns/rust-bcc/blob/f15d2983ddbe349aac3d2fcaeacf924a66db4be7/examples/strlen.rs
- https://github.com/nacardin/ebpf-proxy/blob/master/echo/src/main_ebpf.rs
- https://github.com/iovisor/bpftrace
- https://github.com/alessandrod/bpf_examples/blob/master/src/trace_http/main.rs
- https://github.com/jvns/rust-bcc
- https://github.com/iovisor/bcc/blob/master/examples/tracing/strlen_count.py
- https://github.com/aquasecurity/tracee
- https://github.com/iovisor/bpftrace
- https://github.com/Microsoft/ebpf-for-windows
- https://github.com/kentik/convis
- eBPF verifier tool: https://github.com/torvalds/linux/blob/master/kernel/bpf/verifier.c
- In-kernel cache based on eBPF: https://github.com/Orange-OpenSource/bmc-cache
- A Rust interface for the Linux AF_XDP address family: https://github.com/seeyarh/xdpsock
- https://github.com/parca-dev/parca
- https://github.com/kentik/convis
- https://github.com/fujita/libbpf-async
- https://github.com/cilium/ebpf
- https://github.com/solo-io/bumblebee
- Schedule bpftrace programs on your kubernetes cluster using the kubectl: https://github.com/iovisor/kubectl-trace
- Presentations and docs on BPF: https://github.com/iovisor/bpf-docs/
- eBPF Steering Committee: https://github.com/ebpf-io/bsc
- The Collector Project of Apache SkyWalking based on the eBPF: https://github.com/apache/skywalking-rover
- Learning eBPF resources: https://github.com/mikeroyal/eBPF-Guide
- https://github.com/vbpf/ebpf-verifier
- https://github.com/vbpf
- https://github.com/vbpf/ebpf-samples
- egrets monitors egress : https://github.com/ancat/egrets
- Linux eBPF backdoor over TCP. Spawn reverse shells, RCE, on prior privileged access: https://github.com/kris-nova/boopkit
- capture SSL/TLS text content without CA cert using eBPF: https://github.com/ehids/ecapture
- https://github.com/bpfdeploy-io/bpf-rs
- https://github.com/seek-ret/btfhub-online
- Making containers more secure with eBPF and Linux Security Modules (LSM) : https://github.com/lockc-project/lockc
- Shape your traffic the BPF way : https://github.com/leodido/traffico

## Reddit and twitter threads:

- https://www.reddit.com/r/rust/comments/ojzc3z/implementation_of_an_ebpf_memory_profiler_has/
- https://www.reddit.com/r/kernel/comments/oks79i/a_beginners_guide_to_ebpf_programming_with_go/
- https://www.reddit.com/r/kernel/comments/osmf08/esbpf_embedded_smallest_bpf_framework/
- What tools to use at what level(proficiency) in eBPF: https://twitter.com/brendangregg/status/1439361780010999810
- https://www.reddit.com/r/golang/comments/q5ptus/introducing_parca_open_source_infrastructurewide/
- https://www.reddit.com/r/eBPF/comments/qmgo07/introducing_oxidebpf_a_linux_tool_for_rust_and/
- If a person were interested in getting started with eBPF, where should they go?: https://twitter.com/mttaggart/status/1519758390519545858
- I'm starting a series of tweets to help spread the awareness about how bpftool can help manage BPF objects: https://twitter.com/qeole/status/1101450782841466880

## Videos:

- eBPF superpowers from liz rice: https://www.youtube.com/watch?v=4SiWL5tULnQ
- Using eBPF to measure the k8s cluster health: https://www.p99conf.io/session/using-ebpf-to-measure-the-k8s-cluster-health/
- https://www.p99conf.io/session/high-performance-networking-using-ebpf-xdp-and-io_uring/
- A moderate intro to writing BPF programs with Rust: https://www.youtube.com/watch?v=Pac083l2R34
- https://www.infoq.com/presentations/ebpf-cloud-native/
- eBPF and Go: https://changelog.com/gotime/201
- LPC 2021: BPF And Networking Summit: https://www.youtube.com/watch?v=igJLKyP1lFk
- Cilium - BPF & XDP for containers: https://archive.fosdem.org/2017/schedule/event/cilium/
- BBR-based congestion control for Kubernetes Pods: https://www.youtube.com/watch?v=iiMp3TrDcsc
- BPTGen: https://www.youtube.com/watch?v=zdbCvGSdFiQ
