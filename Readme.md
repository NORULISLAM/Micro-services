# 🎓 University Management System – Full Microservices Project

### 👨‍💻 Developed by Norul Islam (Jewel)

Welcome to my fully scalable **University Management System**, built with a modern microservices architecture. This project was created to demonstrate my real-world skills in backend engineering, API design, distributed systems, authentication, and DevOps.

---

## 🔧 System Architecture Overview

This system is divided into several services for maintainability and scalability:

| Service             | Description                                                            |
| ------------------- | ---------------------------------------------------------------------- |
| **API Gateway**     | Central gateway that routes requests to services (Auth, Core, Payment) |
| **Auth Service**    | Handles login, JWT, role-based auth, and user management               |
| **Payment Service** | Manages transactions, payment records, and billing integrations        |

All services use **TypeScript**, **Express.js**, **Zod**, **MongoDB**, and **Dockerized** for deployment.

---

## 🧱 Microservices Included

### 1. 🔐 Authentication Service

- Role-based login/logout for Student, Faculty, Admin
- JWT authentication + refresh token flow
- CRUD operations for user profiles
- Admin user management (create, update, delete users)

📄 [Auth Service API Docs](https://documenter.getpostman.com/view/26682150/2s93zB72V9)

---

### 2. 💳 Payment Service

- Payment record creation
- Stripe-style endpoint structure
- Microservice-ready and secured by token validation

✅ `yarn dev` in the payment directory to run  
📁 Folder: `university-management-payment-service`

---

### 3. 🌐 API Gateway

- Reverse proxy for routing requests
- Middleware for token validation and request transformation
- Secure routing to `/auth`, `/core`, and `/payment` endpoints

📄 [Gateway API Docs](https://documenter.getpostman.com/view/26694209/2s9YC5zCgD)  
📁 Folder: `university-management-api-gateway`

---

## ⚙️ Technologies Used

- **Node.js**, **TypeScript**, **Express.js**
- **MongoDB** & **Mongoose**
- **Redis** (for caching, sessions)
- **Multer** + **Cloudinary** (media handling)
- **Zod** (data validation)
- **Docker**, **GitHub Actions**, **Postman**
- Deployment-ready structure

---

## 🧪 How to Run All Services (Dev Environment)

```bash
# Clone the full monorepo or microservice repos individually
git clone https://github.com/NORULISLAM/Micro-services.git

# Go into each service and run:
cp .env.example .env
yarn install
yarn dev
```

##Japanese

# 🎓 大学管理システム – マイクロサービス構成プロジェクト

### 👨‍💻 開発者: ノルール・イスラム（Jewel）

本リポジトリは、**大学管理システム**のマイクロサービス構成を採用したバックエンドプロジェクトです。  
API 設計、認証機能、サービス間通信、DevOps のスキルを総合的に活かして構築しました。

---

## 🔧 システム構成概要

このプロジェクトは、以下のような複数のサービスに分かれています：

| サービス名          | 説明                                                         |
| ------------------- | ------------------------------------------------------------ |
| **API Gateway**     | リクエストを各サービスにルーティングするゲートウェイサービス |
| **Auth Service**    | 認証・認可機能、ログイン、ユーザー管理を担当                 |
| **Payment Service** | 支払い情報の管理や取引処理を担当                             |

各サービスは **TypeScript**, **Express.js**, **MongoDB**, **Zod**, **Docker** をベースに構築しています。

---

## 🧱 マイクロサービス詳細

### 1. 🔐 認証サービス（Auth Service）

- 学生・教員・管理者のログイン／ログアウト
- JWT トークンによる認証
- プロフィール更新機能
- 管理者によるユーザー作成・削除・更新機能

📄 [Auth API ドキュメント](https://documenter.getpostman.com/view/26682150/2s93zB72V9)

---

### 2. 💳 支払いサービス（Payment Service）

- 支払い情報の記録
- トークンベースの認証
- API ゲートウェイ経由でのセキュアな通信

📁 ディレクトリ: `university-management-payment-service`  
✅ `yarn dev` で起動

---

### 3. 🌐 API ゲートウェイ（API Gateway）

- すべてのリクエストをマイクロサービスに振り分け
- 認証ミドルウェア
- `/auth`, `/core`, `/payment` エンドポイントへ安全に転送

📄 [Gateway API ドキュメント](https://documenter.getpostman.com/view/26694209/2s9YC5zCgD)  
📁 ディレクトリ: `university-management-api-gateway`

---

## 🛠️ 使用技術

- **Node.js**, **TypeScript**, **Express.js**
- **MongoDB**, **Mongoose**
- **Redis**（キャッシュ管理）
- **Multer**, **Cloudinary**（ファイルアップロード・画像処理）
- **Zod**（バリデーション）
- **Docker**, **GitHub Actions**, **Postman**

---

## 🧪 開発環境での起動手順

```bash
git clone https://github.com/NORULISLAM/Micro-services.git

# 各サービスディレクトリに移動して以下を実行：
cp .env.example .env
yarn install
yarn dev
```
