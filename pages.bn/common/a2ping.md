# a2ping

> চিত্রগুলি কে EPS বা PDF ফাইলে রূপান্তর করুন।
> আরও জানতে: <https://manned.org/a2ping>.

- একটি চিত্রকে PDF তে রূপান্তর করুন (নোট: আউটপুট ফাইল নাম নির্দিষ্ট করা ঐচ্ছিক):

`a2ping {{চিত্র.ext/এর/পথ}} {{আউটপুট.pdf/এর/পথ}}`

- নির্দিষ্ট শৈলীতে ডকুমেন্ট সংক্ষিপ্ত করুন:

`a2ping --nocompress {{none|zip|best|flate}} {{ফাইল/এর/পথ}}`

- যদি উচ্চ রেজোলিউশন বাক্স স্ক্যান করা থাকে তবে HiResBoundingBox (নোট: এটি ডিফল্টভাবে হ্যাঁ):

`a2ping --nohires {{ফাইল/এর/পথ}}`

- মূল পৃষ্ঠার নিচে এবং বামে পৃষ্ঠার কন্টেন্টের অনুমতি দিন (নোট: এটি ডিফল্টভাবে না):

`a2ping --below {{ফাইল/এর/পথ}}`

- `gs` এর জন্য অতিরিক্ত আর্গুমেন্ট পাস করুন:

`a2ping --gsextra {{আর্গুমেন্ট}} {{ফাইল/এর/পথ}}`

- বাহ্যিক প্রোগ্রামে অতিরিক্ত আর্গুমেন্ট পাস করুন (যেমন pdftops):

`a2ping --extra {{আর্গুমেন্ট}} {{ফাইল/এর/পথ}}`

- সাহায্য প্রদর্শন করুন:

`a2ping -h`