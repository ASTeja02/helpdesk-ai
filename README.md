# \# Helpdesk AI Microservice 🧠

# 

# A Spring Boot-based backend system that integrates OpenAI GPT APIs to automate helpdesk support responses for customers.

# 

# ---

# 

# \## 💡 Features

# \- REST API to submit, resolve, and track support tickets

# \- Integrated OpenAI GPT (via mock) to auto-suggest ticket resolutions

# \- JWT + Spring Security-based login system for agents and users

# \- PostgreSQL database for ticket storage and user info

# \- Role-based access control (agent, admin, customer)

# \- Swagger/OpenAPI 3 documentation for all endpoints

# \- Dockerized + CI/CD ready (GitHub Actions)

# \- CORS config, error handlers, centralized logging

# 

# ---

# 

# \## 🧰 Tech Stack

# | Backend        | Spring Boot, Spring Security, Spring Data JPA |

# |----------------|----------------------------------------------|

# | Database       | PostgreSQL |

# | Auth           | JWT (Token-based) |

# | AI Integration | OpenAI API (mocked for demo) |

# | Docs           | Swagger / OpenAPI |

# | CI/CD          | GitHub Actions |

# | Testing        | JUnit 5, Mockito |

# | DevOps         | Docker |

# 

# ---

# 

# \## 🚀 API Documentation

# Run locally, then visit:

# http://localhost:8080/swagger-ui/index.html

# 

# ---

# 

# \## 🏁 Run Project Locally

# 

# 1\. Install Java 11 \& Maven

# 2\. Create PostgreSQL DB `helpdeskdb`

# 3\. Run:

# ```bash

# mvn clean install

# mvn spring-boot:run

