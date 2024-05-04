
# P0wn3d Challenge

Welcome to the P0wn3d challenge repository! This challenge is designed to test your skills in web exploitation, specifically in the area of Local File Inclusion (LFI). The task is to retrieve the password for managing the content of a compromised portal that uses the CMS "cmsimple."

## Challenge Details

- **Name:** P0wn3d
- **Author:** g0uZ
- **Date:** December 27, 2011
- **Level:** Easy
- **Points:** 20

### Description

A small association eager to create a website didn't even have time to install their CMS "cmsimple" before being hacked. Your goal is to recover the password that allows you to manage the portal's content.

### Resources

Here are some useful resources to help you with the challenge:

1. [Exploiting LFI using co-hosted web applications](https://example.com/resource1)
2. [Source code auditing algorithm for detecting LFI and RFI](https://example.com/resource2)
3. [Local File Inclusion](https://example.com/resource3)
4. [Remote File Inclusion and Local File Inclusion explained](https://example.com/resource4)
5. [LFI with phpinfo() assistance](https://example.com/resource5)

## Challenge Files

- **cmsimple3_0.zip:** The CMS that was hacked.

## Getting Started

### Docker Setup

This challenge can be run using Docker. The following steps outline how to set it up:

1. **Clone the Repository:**

   ```bash
   git clone <your-github-repo-url>
   cd <repo-name>
   ```

2. **Build the Docker Image:**

   ```bash
   docker build -t p0wn3d-challenge .
   ```

3. **Run the Docker Container:**

   ```bash
   docker run -p 8080:80 p0wn3d-challenge
   ```

4. **Access the Challenge:**

   Open your browser and navigate to `http://localhost:8080`.

### Instructions

1. **Analyze the CMS:** Start by exploring the CMS files provided in `cmsimple3_0.zip`.
2. **Identify the Vulnerability:** The CMS is vulnerable to Local File Inclusion (LFI).
3. **Exploit the Vulnerability:** Use the LFI vulnerability to access sensitive information, including the password.
4. **Submit the Password:** Once you retrieve the password, submit it to complete the challenge.

## Conclusion

This challenge is a great opportunity to practice LFI exploitation techniques. If you have any issues or want to discuss potential solutions, feel free to open an issue or submit a pull request on this repository.
