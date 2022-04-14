package com.spring.demo;

import org.springframework.beans.factory.annotation.Value;

public class DBSource {
	//@Value("xxx.org")
	String driver;
	//@Value("http;/deselect.com/home")
	String url;
	//@Value("abcdef")
	String username;
	//@Value("1cghy6y")
	String password;
	public DBSource() {
		super();
	}
	public DBSource(String driver, String url, String username, String password) {
		super();
		this.driver = driver;
		this.url = url;
		this.username = username;
		this.password = password;
	}
	public String getDriver() {
		return driver;
	}
	public void setDriver(String driver) {
		this.driver = driver;
	}
	public String getUrl() {
		return url;
	}
	public void setUrl(String url) {
		this.url = url;
	}
	public String getUsername() {
		return username;
	}
	public void setUsername(String username) {
		this.username = username;
	}
	public String getPassword() {
		return password;
	}
	public void setPassword(String password) {
		this.password = password;
	}
	@Override
	public String toString() {
		return "DataSource [driver=" + driver + ", url=" + url + ", username=" + username + ", password=" + password
				+ "]";
	}

}
