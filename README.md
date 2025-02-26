# session-2
### `README.md` (Bangla)  


```markdown
# 🎯 TypeScript মৌলিক চর্চা (Basic Practice)  

এই রিপোজিটরিতে TypeScript এর মৌলিক ধারণা, ফাংশন, অ্যারে, অবজেক্ট, স্ট্রিং, এবং অন্যান্য গুরুত্বপূর্ণ বিষয় নিয়ে আলোচনা করা হয়েছে।  

---

## 🚀 TypeScript কেন ব্যবহার করবেন?  
✅ **Static Typing:** টাইপ সংক্রান্ত ভুল প্রতিরোধ করে।  
✅ **Better Readability:** কোড পরিষ্কার ও সহজে বুঝতে সাহায্য করে।  
✅ **OOP Features:** ক্লাস, অবজেক্ট, ইনহেরিটেন্স ইত্যাদি সহজে ব্যবহারের সুযোগ দেয়।  
✅ **Better Scalability:** বড় প্রজেক্টের জন্য আদর্শ।  

---

## 🛠️ TypeScript সেটআপ ও রান করার নিয়ম  

### 1️⃣ TypeScript ইনস্টল করুন:  
```sh
npm install -g typescript
```

### 2️⃣ নতুন প্রোজেক্ট তৈরি করুন এবং `example.ts` ফাইল যুক্ত করুন।  

### 3️⃣ TypeScript কোড কম্পাইল করুন:  
```sh
tsc example.ts
```

### 4️⃣ JavaScript ফাইল রান করুন:  
```sh
node example.js
```

---

## 📌 **উদাহরণসমূহ**  

### ✅ **১. ফাংশন (Function)**
```typescript
function যোগফল(a: number, b: number): number {
    return a + b;
}

console.log(যোগফল(১০, ৫)); // আউটপুট: ১৫
```

### ✅ **২. অ্যারে (Array)**
```typescript
let সংখ্যা_তালিকা: number[] = [১, ২, ৩, ৪, ৫];

সংখ্যা_তালিকা.push(৬);
console.log(সংখ্যা_তালিকা); // আউটপুট: [1, 2, 3, 4, 5, 6]
```

### ✅ **৩. স্ট্রিং (String)**
```typescript
let নাম: string = "রহমান";
console.log(`আমার নাম ${নাম}`); // আউটপুট: আমার নাম রহমান
```

### ✅ **৪. অবজেক্ট (Object)**
```typescript
let ছাত্র: {নাম: string, বয়স: number, বিভাগ: string} = {
    নাম: "জহির",
    বয়স: ২০,
    বিভাগ: "কম্পিউটার সায়েন্স"
};

console.log(ছাত্র);
```

### ✅ **৫. ইন্টারফেস (Interface)**
```typescript
interface ছাত্র_তথ্য {
    নাম: string;
    বয়স: number;
    বিভাগ: string;
}

let ছাত্র1: ছাত্র_তথ্য = {
    নাম: "রফিক",
    বয়স: ২২,
    বিভাগ: "ইলেকট্রিক্যাল ইঞ্জিনিয়ারিং"
};

console.log(ছাত্র1);
```

### ✅ **৬. Enum (Fixed Value Set)**
```typescript
enum দিন {
    রবিবার, সোমবার, মঙ্গলবার, বুধবার, বৃহস্পতিবার, শুক্রবার, শনিবার
}

let আজ: দিন = দিন.বুধবার;
console.log(আজ); // আউটপুট: ৩ (Index হিসাবে গণনা হয়)
```

### ✅ **৭. ক্লাস ও অবজেক্ট (Class & Object)**
```typescript
class Student {
    নাম: string;
    বয়স: number;

    constructor(নাম: string, বয়স: number) {
        this.নাম = নাম;
        this.бয়স = বয়স;
    }

    display(): void {
        console.log(`নাম: ${this.নাম}, বয়স: ${this.বয়স}`);
    }
}

let student1 = new Student("সাজিদ", ২১);
student1.display(); // আউটপুট: নাম: সাজিদ, বয়স: ২১
```

---

## 🎯 **উপসংহার**  
TypeScript ব্যবহার করলে **বাগ কমে, কোড আরও পরিষ্কার হয়, বড় প্রজেক্ট সহজে মেইনটেইন করা যায়, এবং Static Typing থাকার কারণে ডেভেলপারদের জন্য আরও সুবিধাজনক হয়ে ওঠে।**  

---

## 📜 **TypeScript প্রোজেক্ট রান করার ধাপ:**  
1️⃣ TypeScript ইনস্টল করুন:  
   ```sh
   npm install -g typescript
   ```
2️⃣ একটি `app.ts` ফাইল তৈরি করুন এবং কোড লিখুন।  
3️⃣ TypeScript কোড কম্পাইল করুন:  
   ```sh
   tsc app.ts
   ```
4️⃣ JavaScript ফাইল রান করুন:  
   ```sh
   node app.js
   ```

---
